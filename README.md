# rPPG
This repo measures instantaneous heart rate of a person with remote photoplethysmography(rPPG) without any physical contact, capturing rPPG signal through webcam.

## Pipeline

![](images/pipeline.png)

## Requirements

* Python 3
* Numpy
* Pytorch
* OpenCv
* Matplotlib, Scipy, Pillow
* Git Lfs to track trained model parameters
* We have used semantic segmentation to generate face masks to remove non skin pixels from frames. The Segmentation requires cuda device

Clone this repository.

        git clone https://github.com/nasir6/rPPG.git

To run

        cd rPPG
        python3 run.py --source=0 --frame-rate=25


