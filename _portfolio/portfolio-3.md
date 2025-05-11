---
title: "LAVA: Large Scale Automated Vulnerability Addition"
excerpt: "This is an area of research interest on planting realistic security bugs in C. <br/><img src='/files/images/lava_artwork.png' style='width: 500px; height: 300px;'>"
collection: portfolio
---

LAVA is designed to plant security bugs in C, such as memory errors. The objective is that planting security bugs would help both evaluate fuzzers and also provide more training data as real vulnerability datasets are scarce. 

Research Focus:
1. Upgrade LAVA to create new inputs so that LAVA can plant bugs outside of the 'main path' of code executed by the original input. Emhpasis will be on picking new files that will use branches that fuzzers would struggle with such as complicated evaluations or checking for MAGIC values.

2. Upgrade LAVA to be able to inject bugs into ARM architecture. This would allow for testing fuzzers in ARM environments.

[Code](https://github.com/panda-re/lava)
