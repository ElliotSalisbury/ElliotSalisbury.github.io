---
title: Whale Tracking Hackday
description: This is the description of our sample project
date: "2024-06-26T12:00:00-07:00"
jobDate: 2024
work: [python, drone, computer vision]
techs: [python, drone, computer vision, deep learning]
designs: []
thumbnail: whale-hackday/whales.jpg
projectUrl: http://mlsquamish.ca/past-events/whale-health-hackday/
---

I organised and took part in a [MLSquamish](http://www.mlsquamish.ca/) hackday, aimed to support the research efforts of biologist [David Gaspard](https://www.linkedin.com/in/david-gaspard-79bb29239), who focuses on assessing the health of humpback whales. Gaspard's research involves monitoring the body mass of these whales over time, as it serves as an indicator of their environment's health and their hunting success.
 
Traditionally, scientists have manually reviewed drone footage to select the most suitable images of each whale. Then, he utilizes photogrammetry software to estimate the body mass of the whales by measuring multiple widths down the length  of the whale.

Recognizing the labor-intensive nature of this process, the Machine Learning Squamish community collaborated to explore the potential of computer vision to streamline aspects of Gaspard's work.

We explored the use of a YOLO model and a Segment Anything model to automate the extraction of individual whales within the drone footage. Additionally, an algorithm was explored to identify the optimal frame in the video that would show the maximum visibility of the whales. These results can then be exported to a photogrammetry software enhancing the efficiency of data collection and analysis.
