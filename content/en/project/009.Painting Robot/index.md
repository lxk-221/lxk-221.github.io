---
title: Painting Robot
summary: A Robot for Interior Painting
date: 2023-09-01
type: docs
math: true
tags:
  - Painting Robot
  - Construction Scene
featured: /media/projects/painting-robot/featured.png
---

## Overview
This project is the topic of my Master's thesis. 

In construction spraying operations, spray robots offer significant advantages over manual labor. However, to meet the high precision required, spray robots must accurately perceive large-scale objects. Additionally, the demands of the spraying process require that spray robots incorporate new procedural constraints into their path planning for wall coverage painting. This research will focus on the following aspects. 
1. Perception of large wall surfaces.
2. Coverage path planing for the robot.
3. The software for the whole painting robot on Windows.

## Perception

Initially, we used a region-growing based method for perception, projecting the wall surface onto a 2D plane. This approach effectively transitioned the problem from 3D coverage path planning to 2D coverage path planning.

However, we discovered that this method was inadequate for handling tasks involving corners and curved surfaces. Therefore, we are now exploring a slicing-based method to address these challenges.

## Slicing-Based Painting Trajectory Generation

## Painting Reachability Map Based Trajectory Optimization
### Compact Reach Map
### Painting Reach Map
### Optimization


## Project Status

This project is still in progress...

## Experiments
![Single Spray](/media/projects/painting-robot/single-spray.gif "Single Spray")
![Double Spray](/media/projects/painting-robot/double-spray.gif "Double Spray")
![Wide Range](/media/projects/painting-robot/wide-range.gif "Wide Range")
<!--more-->
