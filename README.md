# singularity-cowsay
![Release](https://img.shields.io/badge/release-prealpha-red.svg)
[![GitHub issues](https://img.shields.io/github/issues/icaoberg/singularity-cowsay.svg)](https://github.com/icaoberg/singularity-cowsay/issues)
[![GitHub forks](https://img.shields.io/github/forks/icaoberg/singularity-cowsay.svg)](https://github.com/icaoberg/singularity-cowsay/network)
[![GitHub stars](https://img.shields.io/github/stars/icaoberg/singularity-cowsay.svg)](https://github.com/icaoberg/singularity-cowsay/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/quick-guide-gplv3.en.html)

A simple container with [cowsay](https://en.wikipedia.org/wiki/Cowsay).

## Building the container
```
bash ./run.sh
```

## List app(s)
```
singularity apps cowsay.simg                                     
cowsay
```

## Get help!
```
singularity help --app cowsay cowsay.simg
    For more information visit http://www.cowsay.org/
```

## Download
```
singularity pull --name cowsay.simg shub://icaoberg/singularity-cowsay
```

## Running the app

```
singularity run --app cowsay cowsay.simg "Bacon pancakes"
```

---
[![CBD](http://www.cbd.cmu.edu/wp-content/uploads/2017/07/wordpress-default.png)](http://www.cbd.cmu.edu)

Copyleft © 2018-2019 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)
