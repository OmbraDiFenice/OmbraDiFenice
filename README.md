# Hello people! 

I'm a backend/full stack developer (yeah, weird mix), very interested and passionate about software design, languages and DYI. 

<a href="https://www.linkedin.com/in/stefano-stoduto-a4859160/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>

## What I'm currently working on

<a href="https://github.com/OmbraDiFenice/gbEmu"><img src="https://gh-card.dev/repos/OmbraDiFenice/gbEmu.svg"></a>

I always wanted to write a gameboy emulator. I think it's a great way to apply many of the things you study about simple computer architectures,
to experiment with new concepts and learn new technologies - even new languages. The hardware it's old enough to be easy to understand, yet it 
is powerful enough to get to run some cool games, which is a big motivational plus :D

I'm using this project specifically to learn a bit of OpenGL and as a training ground for my software design skills, including a generic project
setup like configuration of the build toolchain, dependency management, modularity and CI.

## Some of my projects

<a href="https://www.npmjs.com/package/table2csv"><img src="https://gh-card.dev/repos/OmbraDiFenice/table2csv.svg"></a>

This is a very simple jQuery plugin that allow to export an HTML table as csv.
You can download a csv file directly or just convert it to a string to print out in your page.
Check out the [live demo page](https://ombradifenice.github.io/table2csv/) if you want to try it out.

It's very simple, yet it was useful to me (it is actually a subproduct of a tool I wrote at work a while ago) so I thought to share it and also used it to experiment with a release on npmjs and jQuery.

---

<a href="https://github.com/OmbraDiFenice/ledCubeLib"><img src="https://gh-card.dev/repos/OmbraDiFenice/ledCubeLib.svg"></a>
<a href="https://github.com/OmbraDiFenice/ledCube"><img src="https://gh-card.dev/repos/OmbraDiFenice/ledCube.svg"></a>

This is a library, usable both on Arduino and on RaspberryPi, to drive a DIY built Led cube.
This was my first attempt to work with an Arduino, and it was interesting to work on a resources constrained hardware.

<img src="https://github.com/OmbraDiFenice/ledCubeLib/blob/master/demos/waves.gif" alt="led cube waves effect">

This project features:
 - my own, extremely simple, C++ test framework (inspired by [GTest](https://github.com/google/googletest)) which _can run on Arduino itself_. I just wanted to make sure that I wasn't having any "surprise" with things specific to the hardware
 - some simple utility classes (string and vector), again because I didn't have them available from C++ std lib on Arduino
 - dynamically extensible set of effects that can be played on the cube. Adding a new one is just a matter of creating a new file with the code and calling the dedicated macro to register it in the system

---

<a href="https://github.com/OmbraDiFenice/autoDownloader"><img src="https://gh-card.dev/repos/OmbraDiFenice/autoDownloader.svg"></a>

A simple script to automatically check some sources for new content to download.

I used this to experiment a bit with software design in Python and with [jsonschema](https://json-schema.org/) validation.

Effort was put to make the script easily extensible in many aspects, such as:
 - customizable information provider and downloader
 - hooks to run custom scripts
