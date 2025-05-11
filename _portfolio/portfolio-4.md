---
title: "IoT Inspector"
excerpt: "This is the topic of my PhD Research, the idea is to analyze IoT network traffic, and utilizing labeled network traffic, derive user behavioral and health insights. <br/><img src='/files/images/IoT_Inspector.png' style='width: 500px; height: 300px;'>"
collection: portfolio
---

As Internet of Things (IoT) becomes more prevelent, with new devices such as Amazon Echo, smart TVs, Ring doorbell, etc. there is an extensive set of meta data that can be analyzed. In particular, the focus will be on analyzing IoT network traffic for (with user's consent) making insights on a user's health.

Research Objectives:
1. Work on upgrading [IoT inspector](https://inspector.engineering.nyu.edu/), an open source tool that can be used to crowdsource labels on IoT traffic. These labels can map certain network traffic to a behavior e. g. activating an Amazon echo. Based on this, we want to create a machine learning model that can correctly determine what a user is doing based on network traffic.

2. Once the data is collected and IoT inspector is created, I will be working on [Router Sense](https://routersense.ai/), which is a tool used to correlate with the network traffic to specific health insights.


[IoT inspector core code](https://github.com/nyu-mlab/inspector-core-library)

[IoT inspector client code](https://github.com/nyu-mlab/iot-inspector-client)