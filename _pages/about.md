---
permalink: /
title: "Andrew Quijano's personal website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, I'm Andrew Quijano, a researcher, educator, and industry professional passionate about cybersecurity. I am currently a PhD candidate at New York University, where my research focuses on planting triggerable, verified vulnerabilities into existing program source code. This work has applications in benchmarking the ability of software security tools to detect vulnerabilities and in automatically generating cybersecurity challenges for education. 

In the private sector, I began my career as a Security Testing Analyst at JRI-America, where I worked on security automation and vulnerability remediation. Then I worked at Amazon, where I am an Application Security Engineer, reviewing Amazon applications for security issues. Currently, I am working at Fitch Ratings in the Vulnerability Management team, assisting with automation and ensuring timely remediation of backlogged vulnerabilities.

My past research interests have been diverse. I started my research career with [Kemal Akkaya](https://egr.vcu.edu/directory/kemal.akkaya/) at FIU, where I built a new [secure indoor localization system](https://andrewquijano.github.io/publication/2019-11-04-secure-indoor-localization-1). Then, I took a slight segue into research on computational biology, where, during the COVID lockdown, I had the general intuition to [solve the problem of cutting the minimal number of nodes to make a phylogenetic network tree-based](https://andrewquijano.github.io/publication/2020-11-26-max-cst-2). During my graduate education at Columbia University, I worked with [Professor Steven Bellovin](https://www.cs.columbia.edu/~smb/) in his seminar on anonymity class, where, with my team, [we published a paper in a law journal](https://andrewquijano.github.io/publication/2021-12-30-deep-fakes-3) investigating the feasibility of using copyright law to protect a victim from deep fake non-consensual pornography. When I started my PhD, I began collaborating with Professor [Kemal Akkaya](https://egr.vcu.edu/directory/kemal.akkaya/) again, and we published work on [secure decision tree evaluation](https://andrewquijano.github.io/publication/2024-11-22-level-site-ppdt-5) and [drone collision avoidance](https://andrewquijano.github.io/publication/2024-10-08-drone-collision-avoidance-4) using homomorphic encryption. Finally, I am currently working on publishing my paper from MITLL, which is about using SysML to measure RTO/RPO compliance of an application, informing application owners on where to place security controls to maximize business continuity requirements.

My current research focuses on [LAVA](https://andrewquijano.github.io/portfolio/portfolio-3/). LAVA is a tool first built by [Brendan Dolan-Gavitt](https://www.linkedin.com/in/brendan-dolan-gavitt-3b68154) that is used to plant buffer overflows in C code. Currently, aside from clearing the technical debt, I want to investigate three improvements to LAVA:

* Improving path realism: Currently, LAVA can only plant bugs along the lines of code that are executed by a file input. Utilizing angr, the hope is to use concolic execution to generate new inputs, which should allow LAVA to plant more bugs in less predictable places in source code.
* Realistic Bug Injection: Given how much LLMs have improved, and that code-generating LLMs are trained on massive datasets like GitHub, I want to integrate LAVA with an LLM to create more realistic bugs.
* Automated Exploit Generation: LAVA currently can plant the vulnerability and the trigger. However, it can't generate a security exploit. This would be especially useful to confirm the vulnerability is correctly planted and make LAVA useful for Capture the Flag (CTF) challenges. 

As an educator, I strive to create an engaging and inclusive learning environment. Drawing from my private sector experience, I incorporate real-world examples into my teaching to help students connect theoretical concepts to practical applications. I have served as a Teaching Assistant for courses such as Security I, Security II, and Computer Networks, where I supported students in mastering complex concepts and developing practical skills. I also taught at NYU for 3 semesters from Fall 2023 to Spring 2024, where I brought some course improvements such as autograders and a course material refresh to stay more up to date.

I have published and presented my research at IEEE MASS, IPCCC, and LCN. My teaching efforts have been recognized by my students, and my course material is still used in NYU's Application Security course. You can find more about my [research](https://andrewquijano.github.io/publications/) and [teaching](https://andrewquijano.github.io/teaching/).

Outside of academia, I enjoy exploring my hometown, New York City, with my friends. I also occasionally enjoy watching shows, such as *The Three-Body Problem* and *Spy X Family*. I also enjoy listening to music; I especially love Jazz and LoFi. I’m always excited to connect with others who share similar interests!
