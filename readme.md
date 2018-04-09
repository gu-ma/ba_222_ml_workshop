![hslu logo](images/hslu-logo-xtra-small.png "hslu logo")

# ML / AI Workshop

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/webslides/webslides.svg?style=social)](https://twitter.com/hslu)

## Description

Main repo for the workshop Machine learning in Design & Art @DigitalIdeation - Spring 2018

During the workshop you can choose to use different libraries:

- [ML5js](https://ml5js.github.io/docs/getting-started.html) a simple ML library for the web based on tensorflow.js. 
- [Tensorflow.js](https://js.tensorflow.org/) a library with a more advanced set of options, also for the web.
- [Wekinator](http://www.wekinator.org/) is a software allowing anyone to use machine learning to build new musical instruments, gestural game controllers, computer vision and so on. Wekinator is using OSC protocol and can be used with pretty much any type of programing language, we will use [Processing](https://processing.org/).
- [ML4A OFX](https://github.com/ml4a/ml4a-ofx) A collection of real-time interactive applications and associated scripts for working with machine learning. ML4A-OFX is running on [OpenFramework](http://www.openframeworks.cc/)

## Info

To clone this repo and include all submodules:

**Git version 2.13 and later**

```git clone --recurse-submodules git://xxxxxx.git```

**Git version 2.12 to 1.65**

```git clone --recursive git://xxxxxx.git```

For already cloned repos, or older Git versions init the submodules 'manually' by using:

```
git clone git://thisrepo.git
git submodule update --init
```

## Structure

```
├── examples/           (examples + libraries)
│   ├── 01_01           ...
│   ├── 01_02
│   ├── ...
│   ├── ml5js
│   └── ...
├── slides/             (presentation)
├── resources/          (tba)
└── readme.md           (those instructions)
```