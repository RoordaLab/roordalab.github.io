---
layout: page
title: C-RITE
permalink: /
---


__Consortium for Retinal Imaging and Tracking Experiments__ (C-RITE) is cross-institutional group of [labs](/about/) who use scanning-laser ophthalmoscopy (SLO) to measure structure and function of human and animal visual systems. The mission of C-RITE is to share the technological innovations developed across labs.


## Software 

Below is a list of available software repositories organized by the primary purpose and the lab primarily responsible for its development. Click on the name of the package for more information and a link to the source code. In some cases, the source code is not currently available in a downloadable format and a primary contact who can assist you in obtaining a copy is listed.


| Name | Purpose | Primary development lab |
| ---- |:------- | -----------------------:|
| [AO auto montage](#ao-auto-montaging) | Image processing | Morgan & Brainard |
| [AOMcontrol](#aomcontrol) | Data collection | Roorda |
| [AOSACA](#aosaca) | AO specific tools | Roorda |
| [AOVIS_toolbox](#aovis_toolbox) | Analysis tools | Roorda |
| [AOVIS_projector](#aovis_projector) | Data collection | Roorda |
| [ICANDI](#icandi) | Data collection | Roorda |
| [IGUIDE](#iguide) | Data collection | Harmening |
| [Light propagation model](#light-propagation-model) | Analysis tools | Sincich |
| [Pupil Tracker](#pupil-tracker) | Data collection | Harmening |
| [ReVAS](#revas) | Image Processing | Chung |


### Data collection


#### AOMcontrol

* [Source code](https://github.com/RoordaLab/AOMcontrol)

> A MATLAB gui for controlling a tracking SLO. This software is used for testing visual function. Users specify images and temporal sequences to be rendered through the SLO during an experiment. [Documentation](https://github.com/RoordaLab/AOMcontrol/wiki) of AOMcontrol's purpose and limitations is available.

#### ICANDI

* Source code currently unavailable. Contact Austin Roorda for more information.

> Image capture and delivery interface.

#### IGUIDE

* Source code currently unavailable. Contact Wolf Harmening for more information.

> Description _coming soon_.

#### Pupil tracker

* [Source code](https://github.com/ukb-aoslo/PupilTracker). 

> A stand alone program for pupil tracking during experimental data collection. This program does not require AOMcontrol to run. _See also [AOMcontrol Pupil tracker](https://github.com/RoordaLab/AOMcontrol/wiki/Pupil-tracker)_ for an AOMcontrol integrated solution.

#### AOVIS_projector

* [Source code](https://github.com/RoordaLab/AOVIS_projector)

> A Psychtoolbox based program for controlling an external projector. This program can display fixation targets, eccentricity grids, steady state background fields and fundus images. It's primary purpose is color vision research. In the future, this program will include an option to synchronize frame updates with SLO presented stimuli.

### Image processing

#### AO Auto montaging

* [Source code](https://github.com/BrainardLab/AOAutomontaging)

> Software to process adaptive optics videos and stitch together a montage image. The software has been described in a published manuscript: 
> [M. Chen, R. F. Cooper, G. K. Han, J. Gee, D. H. Brainard, and J. I. W. Morgan, "Multi-modal automatic montaging of adaptive optics retinal images," Biomedical Optics Express, Vol. 7 (12), pp. 4899-4918, 2016.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5175540/pdf/4899.pdf).

#### ReVAS

* Source code coming soon.

> An open-source tool for eye motion extraction from retinal videos obtained with a SLO. ReVAS uses a strip-based image registration program designed for SLO videos by [Scott B. Stevenson, Austin Roorda and Garish Kumar (2010) Proceedings of the 2010 Symposium on Eye-Tracking Research & Applications, Austin, TX.](http://roorda.vision.berkeley.edu/Pubs/StevensoETRA2010.pdf).

### Analysis tools

#### AOVIS_toolbox

* [Source code](https://github.com/RoordaLab/AOVIS_toolbox). 

> A general purpose toolbox for collecting and analyzing retinally targeted psychophysical data. Routines include algorithms for generating cone targeted stimuli, collecting and analyzing color naming, delivery analysis and light capture modeling and converting SLO power readings (microWatts) into photons.

#### Light propagation model

* Source code coming soon. Contact Lawrence Sincich.

> A state-of-the-art model of light delivery and back-scatter in an AOSLO. _Developed by Zander Meadway in the Sincich Lab_. Aspects of this model were presented at ARVO 2017 and 2018. A full publication is in preparation.


### Adaptive Optics specific technology

#### AOSACA

* Source code coming soon. Contact Austin Roorda.

> Wavefront sensing and deformable mirror control loop. 


## Funding

The original suite of software and hardware developed for C-RITE was funded bya National Institute of Health Bioengineering Research Partnership (R01EY023591).
