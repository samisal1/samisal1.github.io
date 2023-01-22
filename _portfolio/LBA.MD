---
title: "Performance Profiling of Load Balancing Algorithms in a Cloud Architecture"
excerpt: "Determining which of four load balancing algorithms is the most efficient."
header:
  image: /assets/img/Code.png
  teaser: /assets/img/Equations.png
gallery:
  - image_path: assets/img/JobScheduler.png
  - image_path: assets/img/JS2.png
  - image_path: assets/img/JS3.png
   
---

Load balancing is the process of distributing job requests among servers. There are many different load balancing algorithms, such as round robin, weighted round robin, and least connections, that can be used to process bioinformatics tools. Cloud computing can be used with bioinformatics to create a BioCloud program. A dynamic load balancing algorithm needs to be developed to properly handle distributing bioinformatics jobs. In this experiment, the FastQC job was used for all test cases. Four algorithms were designed to distribute the one type of job: system load, %CPU, free RAM, and round robin. The results of the data show that the FastQC job is CPU intensive, but not RAM intensive. The most efficient algorithm was %CPU.

[Research Publication](https://ieeexplore.ieee.org/document/9658999)

{% include gallery caption="Figures from this case study" %}

