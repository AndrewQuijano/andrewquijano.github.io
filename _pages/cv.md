---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div style="position: relative; width: 100%; height: 0; padding-bottom: 75%;">
    <object data="https://andrewquijano.github.io/files/Andrew_Quijano_CV.pdf" type="application/pdf" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;">
        <p>Your browser does not support PDFs. <a href="https://andrewquijano.github.io/files/Andrew_Quijano_CV.pdf">Download the PDF</a>.</p>
    </object>
</div>

Objective
======
Andrew Quijano is a current PhD candidate at NYU Tandon, majoring in Computer Science. His dissertation research focuses on creating accurately labeled encrypted network traffic. This would be applicable to creating machine learning models that can make inferences both on human behavior and provide healthcare insights, such as detecting early signs of Alzheimer’s or other cognitive impairments.

Education
======
* Ph.D in Computer Science, New York University, 2028 (expected)
* M.S. in Computer Science, Columbia University, 2022
* M.S. in Cybersecurity, New York University, 2022
* B.S. in Computer Science, Columbia University, 2019
* B.A. in Mathematics, CUNY Queens College, 2019
* A.A.S in Computer Operations: Networking and Security, CUNY LaGuardia Community College, 2015

Work experience
======
**Senior Information Security Analyst**  
*Fitch Ratings*  
*New York, NY*  
*Nov 2025 - Present*  

- Optimized organizational risk posture by triaging 100+ high-severity alerts; performed deep-dive analysis on Wiz (CSPM) and Apiiro (ASPM) findings to distinguish between critical production exploits and low-impact package vulnerabilities, significantly streamlining developer remediation efforts.
- Built a Python-based GitHub Actions compliance scanner and dashboard that parsed YAML workflows, detected CI/CD security misconfigurations, and rolled workflow-level findings up to repository-level risk reporting.
- Implemented data validation, error handling, and visualization pipelines using Pandas, Streamlit, and Altair to help engineering and security teams monitor workflow template compliance and prioritize remediation.

**Application Security Engineer**  
*Amazon*  
*New York, NY*  
*Aug 2022 - May 2025*  

- Remediated **2 critical risks** and **80 high risks** of vulnerabilities detected during security reviews, such as outdated TLS, Log4Shell, Credential/PII Logging, and unauthorized use of HuggingFace AI models, impacting over **3,000 internal applications**.
- Was a core contributor to the BRASR tool, an internal tool used for AWS security misconfiguration scanning, which is used to run multiple cloud scanners and provide a processed report that reports on likely false positives and crowdsourced threat mitigation information which is used within the AppSec organization.
- Identified and remediated five bugs in Nightwolf, Amazon's cloud security misconfiguration scanner, including issues such as missing data encryption in-transit enforcement checks on SQS and false positives on outdated ELB TLS security policies.
- Authored internal AWS security standards and developer-centric documentation for S3, Lambda, and KMS; standardized the implementation of automated CloudWatch alerting to detect and mitigate non-programmatic infrastructure changes across service teams
- Graduate over 50 security certifiers after providing feedback on how to complete a thorough security review
- Provide design and review consultations to application owners of the security impact of new features and integrations

**Adjunct Professor**  
*New York University*  
*New York, NY*  
*Jan 2023 - May 2024*
- Delivered engaging webinars to a diverse cohort of 80+ students, fostering a deep understanding of application security principles and secure coding practices.
- Authored comprehensive, structured documentation and transition guides to ensure seamless onboarding and continuity for future instructors, enhancing the long-term sustainability of the course.
- Created Gradescope autograders for four Application Security assignments related to secure coding practices in C, Android, and Django applications, reducing grading work required by **80%**.
 

**Security Testing Analyst**  
*JRI-America, subsidiary of Sumitomo Mitsui Financial Group (SMFG)*  
*July 2019 - August 2022*

- Automated escalation process for IT Security company policy violations using PowerShell (e.g., incomplete entitlement reviews, unused AD Groups, etc.), reducing policy violations by **80%**.
- Systematized security processes using PowerShell (e.g., admin account management, CyberArk safe management, service account audits), saving the security engineering team **40 man-hours per quarter**.
- Implemented automated vulnerability management metric generation to track and remediate vulnerabilities past SLA dates, providing senior management with visibility on company risk posture.
- Developed a password file remediation process in Python that incorporates automated escalation and remediation tracking, resulting in the removal of over **100 offending files** in shared drives.
- Led the effort to remove TLS 1.0/1.1 from SMBC and group company applications.
- Managed a project to implement InsightAppSec, an application layer vulnerability scanner on externally facing websites, which led to the detection and remediation of **two XSS vulnerabilities**.

Research experience
======
* Summer 2026: Summer PhD SWE Intern, Google, Kirkland, WA.
  * Engineered a deterministic, SQL-driven Perfetto trace evaluation engine to detect Binder IPC transactions and validate AI agent vulnerability report reproduction.
  * Benchmarked agent execution across 33 real-world CVEs, achieving 70% automated bug reachability alongside ~90% trial-over-trial consistency in both trace reachability and SQL query generation.
  * Supervisor: [Hyunwook Baek](https://www.linkedin.com/in/doctor-wooky)
* Summer 2024: Graduate Research Assistant, MIT Lincoln Laboratory, Lexington, MA.
  * Collaborated with MIT LL staff on threat modeling and cyber risk assessment for securing
systems
  * Created, tested, and documented SysML plugin for MagicDraw to aid with cyber risk
assessment methodologies
  * Work and findings over the summer led to a conference paper for EMEASEC 2026 (accepted)
  * Supervisor: [Kyle Denney](https://www.ll.mit.edu/biographies/kyle-w-denney)

* Summer 2021: Graduate Research Assistant, MIT Lincoln Laboratory, Lexington, MA.
  * Upgraded zero-knowledge performance testbed by implementing horizontal scaling, bastion
proxying, and integration tests
  * Written a qualitative analysis report on performers converting real-life problems into a
novel zero-knowledge representation
  * Supervisor: [David Wilson](https://www.ll.mit.edu/biographies/david-wilson)

* Summer 2018: Undergraduate Research Assistant, Columbia University, New York, NY.
  * Created an Android app that can passively collect AP, RSSI, and environmental data
  * Tested an indoor room-level localization system using machine learning techniques on
collected data
  * Supervisor: [Henning Schulzrinne](https://www.engineering.columbia.edu/faculty-staff/directory/henning-g-schulzrinne)

* Fall 2017: REU Research Assistant, CUNY Lehman College, Bronx, NY.
  * Worked collaboratively with a team to analyze phylogenetic tree structures
  * Performed studies on open questions in computational geometry with applications to
biological statistics
  * Supervisor: Professor [Katherine St. John](https://stjohn.github.io/) and Professor [Megan Owen](http://comet.lehman.cuny.edu/owen/)

* Summer 2017: REU Research Assistant, Florida International University, Miami, FL
  * Coded in Java the homomorphic encryption algorithms: Paillier, DGK, and El-Gamal
  * Built a MySQL server that used homomorphic encryption and Wi-Fi signatures for indoor
  * Supervisor: [Kemal Akkaya](https://egr.vcu.edu/directory/kemal.akkaya/)

Awards
======
* 2023 GEM Fellowship - PhD
* 2021 Columbia University Course Assistant Fellowship
* 2020 NYU Cyber Fellows Scholarship
* 2017 Robert M. Lilley Memorial Scholarship
* 2017 Louis Stokes Alliance for Minority Participation Scholarship

Certifications
======
* Dec 2019 - Dec 2023 GIAC Security Essentials Certification (GSEC)
* May 2021 - May 2025 GIAC Web Application Penetration Test (GWAPT)
* Feb 2022 - Feb 2026 GIAC Incident Handling (GCIH)
* Jul 2022 - Jun 2026 GIAC Penetration Tester (GPEN)

Skills
======
* Programming Languages
  * C/C++
  * Java
  * Bash
  * SQL
  * Python
  * CDK
  * Terraform
  * PowerShell

* Development Applications
  * Gradle
  * REST API Development
  * Docker
  * Git
  * GitHub Actions
  * Kubernetes

* Security Applications
  * Nexpose
  * InsightAppSec
  * QRadar
  * CyberArk
  * Varonis
  * IDA Pro
  * Burp Suite

* Soft Skills
  * Project Management
  * Technical Writing
  * Scientific Research
  * Process Automation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

<!--
Service and leadership
======
* Currently signed in to 43 different slack teams
-->