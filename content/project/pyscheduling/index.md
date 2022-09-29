---
title: Pyscheduling
subtitle: Your package to solve scheduling problems
date: 2022-09-29T10:39:58.816Z
summary: >-
  P﻿yscheduling is an open-source python package to solve **scheduling**
  problems. The categories tackled are : Single Machine, Parallel Machines,
  Flowshop and Jobshop. 


  The infrastructure for each category is implemented and open to extension to accept problems with more specificity in terms of constraints and multi-objective opptimization. There are methods going from exact methods, heuristics, metaheuristics, B&B, ...etc to solve the different problems of the given category.
draft: false
featured: false
authors:
  - admin
  - Taha-Arbaoui
  - Akram-Badreddine-Laissaoui
tags:
  - Scheduling
  - Package
  - Metaheuristics
  - Heuristics
  - Benchmark
links:
  - name: Documentation
    icon_pack: fab
    icon: google-drive
    url: https://scheduling-cc.github.io/pyscheduling_doc/
  - url: https://github.com/scheduling-cc/
    name: Github repository
    icon_pack: fab
    icon: github
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
![](pyscheduling_cc-03.png)

P﻿yscheduling is an open-source python package to solve **scheduling** problems. The categories tackled are : Single Machine, Parallel Machines, Flowshop and Jobshop. 

The infrastructure for each category is implemented and open to extension to accept problems with more specificity in terms of constraints and multi-objective opptimization. There are methods going from exact methods, heuristics, metaheuristics, B&B, ...etc to solve the different problems of the given category.

S﻿ingle Machine Scheduling Problems :

* M﻿inimize Total Weighted Lateness.
* M﻿inimize Total Weighted Lateness with release dates.
* M﻿inimize Total Weighted Lateness with sequence dependent setup time.
* M﻿inimize Total Weighted Lateness with release dates and sequence dependent setup time.
* M﻿inimize Maximal Lateness with release dates and precedence constraints.
* M﻿inimize Total Weighted Completion Time.
* M﻿inimize Total Weighted Completion Time with release dates.
* M﻿inimize Maximal Completion Time with sequence dependent setup time.
* M﻿inimize Maximal Completion Time with release dates and sequence dependent setup time.

P﻿arallel Machine Scheduling Problems :

* M﻿inimize Maximal Completion Time with sequence dependent setup time.
* M﻿inimize Maximal Completion Time with release dates and sequence dependent setup time.

F﻿lowshop :

* M﻿inimize Maximal Completion Time.
* M﻿inimize Maximal Completion Time with sequence dependent setup time.

J﻿obshop :

* M﻿inimize Maximal Completion Time.

A﻿n easy-to-use interface is available for both single and parallel machines problems sheduling. In addition to both interfaces, a **benchmark** module is also available to allow it for users and especially researchers to test and benchmark their implemented methods based on our infrastructure with a given instances benchmark set.

T﻿he package is open to contribute for anyone in order to enrich the categories infrastructure, to implement state-of-the-art methods and to tackle more constrained problems.