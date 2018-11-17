# PaperHopper

PaperHopper is a prototype medium for experimenting with how our environment changes how we design.

Initially developed with _Metatool_, a class taught at Columbia GSAPP in Fall 2018. Students are asked to brainstorm and create experimental environments that altered their design process.

Heavily inspired by [Dynamicland](https://dynamicland.org/).

Developed to be used with Rhino/Grasshopper, PaperHopper is somewhere between tool and medium. It is also very much a prototype.

## Setup

### Hardware

(More details to come)

Required hardware:
- A table with a light-ish surface. The maximum size will depend on the projector throw distance and the webcam angle of view.
- People
- Webcam.
  - The more resolution, the better, and also the slower. 1920x1080 at 24fps is ideal. The Logitech Brio is a stellar webcam.
  - The webcam may need some modification to make it into an infrared webcam.
- Projector. 
  - The more lumens, the better. Having a throw ratio of around 0.5 - 1.2 is necessary to get a wide image with a short distance.
- A fast computer with good CPU clock speed. 
  - Grasshopper works on the CPU, and is mostly single-threaded.

### Software

#### Setup for Camera-only mode.

Steps:
  - Download this repo. Everything for PaperHopper is in the `PaperHopper/` subfolder.
  - In the `reacTIVision-1.5.1-win64/` folder, run `reacTIVision.exe`. You should see a screen pop up, showing a processed black-and-white view of the webcam.
    - (This is the same code from `http://reactivision.sourceforge.net/`, just with some settings pre-tweaked for convenience.)
    - Print out a sheet of fiducial markers from `http://reactivision.sourceforge.net/data/fiducials.pdf`, or load it on your phone, and test to see if Reactivision recognizes it. You should see small green numbers in the middle of each markers if so.




