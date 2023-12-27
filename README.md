# SRSU: An Online Road Map Detection and Network Estimation for Structured Bird’s-Eye View Road Scene Understanding

Code will be released after the paper is published.

## Introduction
This paper proposes SRSU, an online road map detection and network estimation method for structured BEV road scene understanding. Specifically, we propose a hierarchical map (including road maps and networks) representation that can accurately describe the fine-grained boundaries in road maps and the rich topology in road networks under a unified framework. Based on the above representation, we propose a hierarchical map construction network, which takes onboard surrounding monocular camera images as input and online generates road maps and networks in a unified framework to achieve a comprehensive understanding of the road scene. Furthermore, we propose auxiliary task prediction, multi-modal distillation, and higher-order interaction modules to improve the accuracy of structured BEV road scene understanding.

## Visualization results under different weather conditions
We visualize the results of SRSU under different weather conditions on the nuScenes val set. Visualization results show that the SRSU achieves
stable and impressive results in all weather conditions.

### Part1: Visualization results under sunny and cloudy weather
![image](https://github.com/jiapeng789/SRSU/blob/main/assets/sunny_and_cloudy.jpg)

### Part2: Visualization results under rainy weather
![image](https://github.com/jiapeng789/SRSU/blob/main/assets/rainy.jpg)

### Part3: Visualization results under nighttime weather
![image](https://github.com/jiapeng789/SRSU/blob/main/assets/nighttime%20.jpg)
