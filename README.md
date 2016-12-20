# Brand Identity and Style Guide

Identity and style guidelines for the BitBrew brand.

## Setup

If you have [Bundler](http://bundler.io/), you can install all dependencies from the `Gemfile` at one time using:

```
bundle install
```

Otherwise, install each dependency manually using:

```
gem install sass
gem install susy
```


## Compiling SASS

Watch for changes and compile automatically:

```
sass --watch scss:css --require susy
```

Explanation:
* `--watch scss:css`: Watches /scss directory for changes, compiles to /css directory when change is made
* `--require susy`:   obv


Compile manually
```
sass --update scss:css --require susy
```

Explanation:
* `--update scss:css`: Manual equivalent of watch


*Compile with CSS Minification:*

include the following flag to minify:
```
--style compressed
```
