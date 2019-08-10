# STYLEGAN ANIMATIONS
Using RunwayML and P5.js

## RESOURCES

* [Companion Tutorial Video to this codebase](https://youtu.be/a9lVZ2eGheE)

![Animated StyleGAN Transitions with Runway and P5](https://prototypes.mikeheavers.com/transfer/stylegan-transitions.gif)


### DOWNLOADS
* [P5.js](http://p5js.org/) - Requests random images from StyleGAN and saves them to your computer
* [Runway](https://runwayml.com/) - Generates the StyleGAN images for P5
* [P5 Dom](https://p5js.org/reference/#/libraries/p5.dom) - Allows you to save files from P5 canvas images
* [Toxic Libs](http://haptic-data.com/toxiclibsjs) - Generates the simplex noise in order to randomize our images

### EXAMPLES

* [Coding Train Introduction to Runway](https://www.youtube.com/watch?v=QzRW0xzm10c&t=6622s)
* [Accompanying P5 Sketch to Generate Rainbow Images](https://editor.p5js.org/codingtrain/sketches/K6l0JbS6u)
* [Original Code from Shiffman for creating animated transition between images](https://editor.p5js.org/codingtrain/sketches/KVXguIFNg)
* [My adapatation](https://github.com/heaversm/runway-stylegan-animations)

### MORE INFO

* [Intro to StyleGAN](https://www.youtube.com/watch?v=-cOYwZ2XcAc)

## INSTRUCTIONS

* Download, install and run Runway 
* Download P5, P5 Dom, and ToxicLibs
* Create a workspace in runway running StyleGAN
* In runway under styleGAN options, click Network, then click "Run Remotely"
* Open the `index.html` file from the github repo in your browser.
* To output a video from Runway, choose Output > Video and give it a place to save and select your desired frame rate.
* To output a video from Processing, turn the images output from the browser from an image sequence to a video using a tool like Premiere / AfterEffects, or other free online resource.

