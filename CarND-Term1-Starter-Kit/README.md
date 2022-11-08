# CarND
In this repository I'll share source code from projects of [Udacity's Self Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013)

## If you have already installed the [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) you should be good to go!   If not, you should install the starter kit to get started on this project. !!! Please use the environment.yml from this repository!!! ##

Set up the CarND Term1 Starter Kit if you haven't already like described below.

## Table of Contents

#### [P1 - Finding Lane Lines](CarND-LaneLines-P1)
 - **Summary:** Identify lane lines on the road, first in an image, and later in a video stream.
 - **Keywords:** Computer Vision, Lane Lines

#### [P2 - Advanced Lane Lines](CarND-Advanced-Lane-Lines-P2)
 - **Summary:** TBD
 - **Keywords:** Comuter Vision, Lane Lines

#### [P7 - Highway Driving](Todo)
- **Summary:** Build a path planner that creates smooth, safe trajectories fon a highway track that has other vehicles, all going different speeds, but approximately obeying the 50 MPH speed limit.
- **Keywords:** Path Planning, Highway Driving

# CarND Term1 Starter Kit

[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

The purpose of this project is to provide unified software dependency support for students enrolled in Term 1 of the [Udacity Self-Driving Car Engineer Nanodegree](https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013).

Python 3 is used for the entirety of term 1.

There are two ways to get up and running:

## [Anaconda Environment](doc/configure_via_anaconda.md)

Get started [here](doc/configure_via_anaconda.md). More info [here](http://conda.pydata.org/docs/).

Supported Sytems: Linux (CPU), Mac (CPU), Windows (CPU)

| Pros                         | Cons                                               |
|------------------------------|----------------------------------------------------|
| More straight-forward to use | AWS or GPU support is not built in (have to do this yourself)              |
| More community support       | Implementation is local and OS specific            |
| More heavily adopted         |                                                    |

## [Docker](doc/configure_via_docker.md)

Get started [here](doc/configure_via_docker.md). More info [here](http://docker.com).

Supported Systems : AWS (CPU, [GPU](doc/docker_for_aws.md)), Linux (CPU), Mac (CPU), Windows (CPU)

| Pros                                | Cons                                 |
|-------------------------------------|--------------------------------------|
| Configure once for all environments | More challenging to use              |
| AWS, GPU support                    | Less community support               |
| Practice with Docker              | Have to manage images and containers |
|                                     |                                      |

## Trouble Shooting

If you get an Import Error on cv2 and have ROS installed. See [here](https://stackoverflow.com/questions/43019951/after-install-ros-kinetic-cannot-import-opencv#).