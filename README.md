# PHP Dependencies [![Build Status](https://travis-ci.com/mihaeu/php-dependencies.svg?token=6E2gXvaZaEh2XxFCPhrX&branch=develop)](https://travis-ci.com/mihaeu/php-dependencies) ![License MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat) [![Gitter](https://img.shields.io/gitter/room/mihaeu/php-dependencies.svg?maxAge=2592000&style=flat)]()

## Roadmap

### Must have

 - detects explicit dependencies (static calls, new, foreign objects, ...)
 - detects implicit dependencies for popular DICs
 - Visualization
 - filters/ignore

### Nice to have

 - CI integration
 - IDE integration
 - fancy visualization (e.g. UML)

## Similar Tools

### PHP

 - [pdepend by Manuel Pichler](https://github.com/pdepend/pdepend) does not support PHP 7
 - [PhpDependencyAnalysis by Marco Muths](https://github.com/mamuz/PhpDependencyAnalysis) does not support PHP7
 - [Deptrac by Sensiolabs DE](https://github.com/sensiolabs-de/deptrac) dependency constraints only, not tested with PHP7

### Other languages

- [jdepend by Clarkware](http://clarkware.com/software/JDepend.html) (Java)

## Other documents

 - [/doc](doc/README.md)
 - [Master Thesis](https://github.com/mihaeu/static-dependency-analysis)

## License

See `LICENSE` file
