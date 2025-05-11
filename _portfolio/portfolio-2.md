---
title: "Treespace Working Group - Python scripts"
excerpt: "This code computes metrics for rooted phylogenetic networks <br/><img src='/files/images/phylogenetics.png' style='width: 500px; height: 300px;'>"
collection: portfolio
---

TreeSpace, as introduced in the work by Francis Steele and collaborators, refers to a mathematical space specifically designed for analyzing phylogenetic trees or, more broadly, tree-structured data. A tree-based network is one that can be constructed from a base tree (a phylogenetic tree) by adding edges—often to model phenomena like recombination or horizontal gene transfer—while retaining the underlying hierarchical structure.

This concept is important because many evolutionary, biological, and network processes are best understood through the lens of tree-like relationships, which capture the flow of information, inheritance, or dependency. Analyzing such networks in TreeSpace enables researchers to rigorously measure distances between different evolutionary hypotheses, optimize likelihood functions, and detect structural changes. The concept of being tree-based thus provides a framework for combining the interpretability and analytical tractability of trees with the complexity needed to model real-world scenarios.

Here is the [Python Code](https://github.com/AndrewQuijano/Treespace_REU_2017/), this computes various metrics that determine how far a network is from being tree-based. 

To access documentation for the code, you can find it [here](http://andrewquijano.github.io/files/treespace_metrics/). 

You can also [download the package via pip](https://pypi.org/project/treespace-metrics/).
