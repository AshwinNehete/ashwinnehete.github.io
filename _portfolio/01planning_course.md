---
title: "Planning and Decision Making in Robots"
excerpt: ""
collection: portfolio
youtubeId: jR8JFaymbeE
---

`Coursework - Fall 2021`

## Motion Planning for Precise Scanning of Additively Manufactured Parts
`Term Project`

* Implemented PRM algorithm to develop a roadmap of the robotic manipulator scanning environment.
* The motion plan construction was guided by A* search using a joint space heuristic function.
* The motion planner thus developed is an important module in a robotic inspection system to traverse an ordered set of scan path waypoints.
* Conducted a parametric study based on the metrics listed below to determine the best parameters to use for the roadmap.
    * No. of vertices
    * No. of connected components
    * Avg. no. of neighbors of each node
    * PRM build time
    * Avg. query time
    * Avg. path cost
    * Success rate
* Currently working on simultaneous motion planning of the DENSO robotic arm and turntable for scanning.

{% include youtubePlayer.html id=page.youtubeId %}

<!-- > Quote -->

<!-- <br/><img src='/images/slam_pic_adobespark.png'> -->

## Catch me if you can!
* Developed a planner that allowed a point robot to catch a moving object.

## Planning for High-DOF planar arm
* Implemented different sampling-based planners for the arm to move from its start joint configuration to a goal configuration avoid collision with the obstacles.
* The types of planners included Probabilistic Roadmaps, RRT, RRT-Connect, RRT*

## Symbolic Planning
* Programmed a generic symbolic planner. The planner takes in a set of symbols, initials conditions, goal conditions as part of the environment description.
* Given a set of valid actions, the planner is able to generate a logical plan to achieve the goal condition.