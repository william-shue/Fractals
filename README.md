# Fractals

## Introduction
This repository contains C programs which draw fractals using the formulas for creating the Mandelbrot and Julia sets.

To best understand the Mandelbrot set I highly recommend reading over it's Wikipedia page: [https://en.wikipedia.org/wiki/Mandelbrot_set](https://en.wikipedia.org/wiki/Mandelbrot_set)

## Repository Structure
The repository structure is as follows:
* 'fractal-programs' contains the C programs which will produce the fractal images
* 'pgms' contains the (portable grey map images) of the fractals produced by the programs
* 'readme-images' contains the images seen below

## Examples
Here are some images to get an idea for what can be created with the following programs:

This is just one example of a Julia set:
![Julia Set Example](https://github.com/william-shue/Fractals/blob/master/readme-images/julia-set-example.png)

Then we have the classic Mandelbrot set:
![Mandelbrot](https://github.com/william-shue/Fractals/blob/master/readme-images/mandelbrot-set.png)

I've also produced the cubic Mandelbrot set:
![Mandelbrot](https://github.com/william-shue/Fractals/blob/master/readme-images/mandelbrot-set-cubic.png)

As well as the quartic Mandelbrot set:
![Mandelbrot](https://github.com/william-shue/Fractals/blob/master/readme-images/quartic-mandelbrot-set.png)

And the quintic Mandelbrot set:
![Mandelbrot](https://github.com/william-shue/Fractals/blob/master/readme-images/quintic-mandelbrot-set.png)

## Use
If you're familiar with compiling C programs in terminal then this should be a breeze for you! In the 'fractal-programs' file just target fractal file you're interested in, compile it (I like using gcc) and then run the executable. This will produce a pgm image which can be viewed with an application like 'preview'.
