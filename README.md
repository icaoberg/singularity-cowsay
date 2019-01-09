# singularity-figlet
![Release](https://img.shields.io/badge/release-prealpha-red.svg)
[![GitHub issues](https://img.shields.io/github/issues/icaoberg/singularity-figlet.svg)](https://github.com/icaoberg/singularity-figlet/issues)
[![GitHub forks](https://img.shields.io/github/forks/icaoberg/singularity-figlet.svg)](https://github.com/icaoberg/singularity-figlet/network)
[![GitHub stars](https://img.shields.io/github/stars/icaoberg/singularity-figlet.svg)](https://github.com/icaoberg/singularity-figlet/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://www.gnu.org/licenses/quick-guide-gplv3.en.html)

```
__   __
\ \ / /__  _   _    __ _ _ __ ___
 \ V / _ \| | | |  / _` | '__/ _ \
  | | (_) | |_| | | (_| | | |  __/
  |_|\___/ \__,_|  \__,_|_|  \___|


  __ ___      _____  ___  ___  _ __ ___   ___
 / _` \ \ /\ / / _ \/ __|/ _ \| '_ ` _ \ / _ \
| (_| |\ V  V /  __/\__ \ (_) | | | | | |  __/
 \__,_| \_/\_/ \___||___/\___/|_| |_| |_|\___|

```

A simple container with [FIGlet](https://en.wikipedia.org/wiki/FIGlet).

## Building the container
```
bash ./run.sh
```

## List app(s)
```
singularity apps figlet.simg                                     
figlet
```

## Get help!
```
singularity help --app figlet figlet.simg
    For more information visit http://www.figlet.org/
```

## Running the app

```
singularity run --app figlet figlet.simg "Bacon pancakes"
 ____                                                      _
| __ )  __ _  ___ ___  _ __    _ __   __ _ _ __   ___ __ _| | _____  ___
|  _ \ / _` |/ __/ _ \| '_ \  | '_ \ / _` | '_ \ / __/ _` | |/ / _ \/ __|
| |_) | (_| | (_| (_) | | | | | |_) | (_| | | | | (_| (_| |   <  __/\__ \
|____/ \__,_|\___\___/|_| |_| | .__/ \__,_|_| |_|\___\__,_|_|\_\___||___/
                              |_|
```

---
[![CBD](http://www.cbd.cmu.edu/wp-content/uploads/2017/07/wordpress-default.png)](http://www.cbd.cmu.edu)

Copyleft © 2018 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)
