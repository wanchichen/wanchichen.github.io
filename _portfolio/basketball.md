---
title: "Basketball Tracker"
excerpt: "Live ball tracking in video <br/><img src='https://raw.githubusercontent.com/brettfazio/CVBallTracking/main/assets/bron.gif'>"
collection: portfolio
---

![](https://raw.githubusercontent.com/brettfazio/CVBallTracking/main/assets/bron.gif)

[Brett Fazio](https://www.linkedin.com/in/brett-fazio/) and I created a pipeline for tracking basketballs in video for our graduate level Computer Vision course.

We used a pre-trained [YOLO](https://pjreddie.com/darknet/yolo/) model for initial bounding box detection and [Discriminative Correlational Filters](https://arxiv.org/abs/1611.08461) for live tracking, even without GPUs. We also implement a way to boost accuracy for non-live videos by tracking the object both forwards and backwards.
