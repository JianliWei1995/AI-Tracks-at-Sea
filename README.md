# Artificial Intelligence Technique for Trajectory Estimation of Maritime Vessel

## Problem Statements
AI tracks at sea challenge solicits software solutions to automatically generate georeferenced tracks of maritime vessel traffic based on the data recorded from a single electro-optical camera imaging the traffic from a moving platform. There are a number of challenges that needs to be addressed for a successful submission, which include:
1)	Detection and tracking the target boat precisely. The challenge includes several similar boats on the sea simultaneously. Among these, the goal is to detect and track a single boat defined by the challenge organizers
2)	Defining the geometric relation between coordinate systems. The GPS provides spherical coordinates of latitude and longitude in the world frame. The image, on the other hand, is defined in the local camera centered coordinates, aka image frame. The coordinates of the boats detected in the image needs to be converted to the world frame.
3)	Tracking the target boat in real time. The camera is stationary, but the boat is in motion and at times leave the camera field of view. A continuous tracking strategy needs to be built that can identify the target boat from among similar looking other boats in real time and should be able to relabel the out-of-range boat once it gets back into view.
4)	Develop an end-to-end AI solution: The solution should utilize the strategies and recent advancements in the literature to resolve this problem.
5)	Achieve acceptable accuracy and precision that reduce geolocation errors.

## Deliverables
[[`paper`](https://arxiv.org/abs/2109.01235)] [[`video`](https://youtu.be/0CrNUJH9Ueg)]
[poster](https://github.com/JianliWei1995/Track-at-the-Sea-2020/blob/main/JianliWei_poster.pdf)
