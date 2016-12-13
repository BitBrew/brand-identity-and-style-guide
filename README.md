# Brand Identity and Style Guide

Identity and style guidelines for the BitBrew brand.

## Setup

SASS:
`gem install sass`

SUSY:
`gem install susy`


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
