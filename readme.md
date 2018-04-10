![hslu logo](images/hslu-logo-xtra-small.png "hslu logo")

# ML / AI Workshop

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/webslides/webslides.svg?style=social)](https://twitter.com/hslu)


## Description

Main repo for the workshop Machine learning in Design & Art @DigitalIdeation - Spring 2018

You can choose to use different libraries, ordered below by descending level of abstraction (from higher to lower level):

1. ### [Wekinator](http://www.wekinator.org/) 

   Wekinator is a software allowing anyone to use machine learning to build new musical instruments, gestural game controllers, computer vision and so on. Wekinator is using OSC protocol and can be used with pretty much any type of programing language. We will use it with [Processing](https://processing.org/). 

   * [Example](http://www.wekinator.org/examples/)
   * [Quick Start Pack](http://www.wekinator.org/examples/#Quick_Start_Pack)

2. ### [ML5js](https://ml5js.github.io/) 

   ML5.js is a simple ML library for the web based on tensorflow.js. 

   * [Getting started](https://ml5js.github.io/docs/getting-started.html)
   * [Experiments](https://ml5js.github.io/en/experiments.html)
   * [Git source](https://github.com/ml5js)

3. ### [Brain.js](https://github.com/BrainJS/brain.js) 

   Neural networks in JavaScript, simple and playful.

   * [Great tutorial 01](https://scrimba.com/c/c36zkcb)
   * [Tutorial 02](https://www.youtube.com/watch?v=9Hz3P1VgLz4)
   * [Tutorial 03](https://www.youtube.com/watch?v=lvzekeBQsSo)

4. ### [Tensorflow.js](https://js.tensorflow.org/)

   A library with a more advanced set of options, also for the web.

   * [Getting Started](https://js.tensorflow.org/#getting-started)
   * [Tutorials](https://js.tensorflow.org/tutorials/)
   * [Keynote](https://www.youtube.com/watch?v=YB-kfeNIPCE)

5. ### [ML4A OFX](https://github.com/ml4a/ml4a-ofx) 

   A collection of real-time interactive applications and associated scripts for working with machine learning. ML4A-OFX is running on [OpenFrameworks](http://www.openframeworks.cc/). 

   * [Guides](https://ml4a.github.io/guides/)
   * [Git](https://github.com/ml4a)

5. ### [OFX MSATensorflow](https://github.com/memo/ofxMSATensorFlow) 

   [OpenFrameworks](http://www.openframeworks.cc/) addon for Google's graph based machine intelligence / deep learning library TensorFlow.


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