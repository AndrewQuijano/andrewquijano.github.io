---
title: "Application Security - New York University"
collection: teaching
type: "Class"
permalink: /teaching/nyu-application-security
venue: "New York University, Computer Science and Engineering"
date: 2023-09-01
location: "New York, NY"
---

I was an Adjunct Professor for the Cyberfellows Application Security course for the following semesters: Spring 2023, Fall 2023, Spring 2024.

In the Spring 2023 and Fall 2023 semesters, I was co-teaching with [Kevin Gallagher](https://kgallagher.me/). In my last semester in Spring 2024, I was co-teaching with [Robert Cimarelli](https://engineering.nyu.edu/faculty/robert-cimarelli).

As this is part of the Cyberfellows program, the course is entirely online and is specifically tailored for students who work full-time. Therefore, the course was asynchronous, but I still expected the four projects to be completed over the course of the semester to avoid anyone attempting to cram all assignments at the end of the semester.

Course Content
======
The course used a similar syllabus to [this](https://kgallagher.me/assets/syllabi/ApplicationSecurity.pdf).

The four homework assignments are found here:
1. [Homework 1: Beware of Geeks Bearing Gift Cards](https://github.com/NYUAppSec/appsec_hw1). This homework involves finding and remediating bugs such as segmentation faults in a C program. Also, this assignment covers using a fuzzer to help find bugs and code coverage testing.

2. [Homework 2: When a Wreck Reaches the World Wide Web](https://github.com/NYUAppSec/appsec_hw2). This homework involves finding and remediating XSS, CSRF, OS Injection, and SQL Injection on a buggy Django web application. Then add encryption to the SQLite database.

3. [Homework 3: Deployment Gone Wrong](https://github.com/NYUAppSec/appsec_hw3). This homework involves the security issues around Kubernetes. The first part is about utilizing Kubernetes Secrets instead of hard-coded secrets. The second part is how to enable monitoring of your web application with Prometheus.

4. [Homework 4: Mobile Mess](https://github.com/NYUAppSec/appsec_hw4). This homework involves being given an Android application that has some security issues, and more importantly, removing code that could be invasive to a user's privacy.

Teaching Philosophy
======
1. I believe in the idea that education should attempt to follow the idea that everyone should have their own [digital Aristotle](https://www.youtube.com/watch?v=7vsCAM17O-M). On my end, I felt that I could leverage the fact this course is asynchronous and allow for students to submit their assignments to an autograder to get real-time feedback. The intention was that the autograder can detect common errors and provide hints in each step of the way to completing an assignment. A write-up was still expected to confirm students knew what they were doing rather than attempting to brute force the autograder.

2. Most of the assignments were created by [Kevin Gallagher](https://kgallagher.me/) in Fall 2020. Therefore, by the time I took over, the material needed some important updates. My updates are covered in the next section for each homework.

3. I wanted the course to match as closely as possible to the on-campus experience. With the help of Professor [Brendan Dolan-Gavitt](https://engineering.nyu.edu/faculty/brendan-dolan-gavitt), his recorded lectures in the Spring 2024 semester were added to the NYU Application Security Cyberfellows course.

Accomplishments and Innovations
======
1. Two pull requests [here](https://github.com/gradescope/gradescope-utils/pull/35) and [here](https://github.com/gradescope/gradescope-utils/pull/36), where I figured out how to combine Django with Gradescope. This was important as it was unknown if you could have Homework 2 onboarded into Gradescope. Also, this means that a CTF could leverage Gradescope.
2. Every homework assignment now has an autograder.
3. The homework assignments were upgraded as follows with their justification:
   - **Homework 1**: Beware of Geeks Bearing Gift Cards
     - We added more fuzzing hints as students struggled with this part of the assignment.
     - New Python code was added to help students generate the inputs to the C program to crash it.
     - The autograder uses exit codes to confirm a segmentation fault. This guidance would be returned in Gradescope if the application correctly crashed or gracefully exited.
   - **Homework 2**: When a Wreck Reaches the World Wide Web
     - Standardized the assignment for students to specifically find 4 specific vulnerabilities. This made it easier for building the autograder and helped students to concentrate on specific vulnerabilities.
   - **Homework 3**: Deployment Gone Wrong
     - Added a new part that requires students to learn how to publish images to DockerHub. This is crucial because DockerHub is the most widely used platform for sharing and distributing Docker images, making it an essential skill for real-world DevOps and software deployment workflows. Additionally, this provides an opportunity to demonstrate another practical use of GitHub Actions, showcasing its integration capabilities for automating CI/CD pipelines.
     - Kubernetes Secrets pose security risks because credentials are stored in plain text within the cluster, making them vulnerable to unauthorized access. To address this, students are now required to use Sealed Secrets, which encrypt Kubernetes Secrets and ensure they can only be decrypted by the target cluster. This teaches students a more secure and practical approach to managing sensitive data in real-world Kubernetes environments.
   - **Homework 4**: Mobile Mess
     - Since Android uses Gradle, the homework has been updated to require students to enable testing with Gradle and automate the process using GitHub Actions. This change reinforces the importance of maintaining good CI/CD and testing practices, demonstrating that these principles can be effectively applied to mobile application development.
     - Updated the Android application Gradle version and SDK to avoid technical debt. Additionally, I added more documentation on how to set up Android Studio to assist students in getting started with the project.

Future Contributions and Impact
======
1. The autograders have been documented and transitioned for use in the Fall 2024 semester course taught by Professor Allon Hillel-Tuch and Professor Jonathan Mann.
2. I have created a [public-facing documentation](https://github.com/NYUAppSec/) for the course and documented information such as how to set up EdStem, GitHub Classroom, etc.

Acknowledgements
======
I'd like to thank my course assistants, for they have been instrumental in helping me with refreshing the course material and creating/debugging the autograders:

1. Hemant Pandey (Spring 2023)
2. Sarthak Bohra (Spring 2023)
3. Gaurav Chauhan (Spring 2023)
3. Mauro de los Santos Nodar (Fall 2023)
4. Ethan Bootehsaz (Fall 2023 - Spring 2024)
5. Rohan Ahuja (Fall 2023 - Spring 2024)
6. Robert Todora (Spring 2024)

Accolades
======
[Lalitha Chavali](https://www.linkedin.com/posts/lalitha-bhanu-chavali_ms-cyber-security-activity-7138264448699469825-LlIQ/)

[Adin Drabkin](https://www.linkedin.com/posts/adindrabkin_excited-to-announce-that-i-completed-my-masters-activity-7305241844123058179-6y6R)
