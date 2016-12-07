---
layout: default
title: Home
permalink:
---

## What is SLAM?
  Simultaneous localization and mapping (SLAM) is a popular technique used by autonomous vehicles for creating maps of an environment while tracking the location of the vehicle within the environment (Maxwell, 2013). This technique was pioneered in 1986 by R.C. Smith and P. Cheeseman in their article “On the Representation and Estimation of Spatial Uncertainty” and has been further advanced by Hugh F. Durrant-Whyte. In one of his articles published in the IEEE, Whyte described SLAM as the “Holy Grail” of autonomous vehicle research because “it eliminates the need for artificial infrastructures or a prioritopological knowledge of the environment” (Durrant-Whyte, H. F., 2001, June). There have been several theoretical techniques developed to do SLAM including EKF SLAM and FastSLAM, but there is not a technique or system that can successfully solve all facets of SLAM in a real-world environment (Milford, M. J., 2008).

## Problem Statement
  Current SLAM systems use sonar, pressure sensors, and/or infrared sensors to preform SLAM. The pressure sensors help the robot adjust to barriers that the sonar and infrared sensors may have missed. Our client, Dr. Choi, has requested a physical robot, Thumper, be designed to perform SLAM in an unknown environment. Our client has also requested we use two new devices, the ZED Stereo Camera and Jetson TX1 Graphical Processing Unit (GPU) that have been developed to perform SLAM faster and more accurately than earlier systems. In order to confirm a SLAM system using these two devices would be optimal to preform SLAM, we will analyze the system along with two other systems against feasibility and merit criteria determined by our client and our team to either confirm or reject this claim. 

## Project Goal
  The goal of this senior design project is to provide Dr. Choi with an optimized SLAM system. The operational goal of the completed SLAM and Thumper system is to be able to map an unknown environment while simultaneously localizing its position within the given environment.
