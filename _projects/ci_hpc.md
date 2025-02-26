---
layout: page_project
title: Continuous integration for HPC codes
date: 2022-02-11
updated: 2022-02-11
navbar: Research
subnavbar: Projects
project_url:
status: starting
topics:
  - storage
keywords:
  - CI pipelines
  - Research software engineering
  - Workflows
head: speck_r
members:
  - kabadshow_i
  - murai_h
  - nakamura_y
  - bosilca_g
---

## Research topic and goals
Scientific software is becoming increasingly important for the success of research and to generate new knowledge. Certain codes, critical for a scientific field, have all the characteristics of a research infrastructure: they are developed and maintained over decades, must meet the highest quality requirements, and need specialized personnel for operation and training of users. Therefore, Research Software Engineering (RSE) is forming as a new subject of investigation in many research centers, universities and laboratories.

For HPC codes, clean and careful software engineering becomes even more crucial, but also more challenging. This is in particular true for continuous testing, integration, benchmarking, deployment (CT/CI/CB/CD = Cx): different architectures, different compilers, different degrees and types of parallelism, different software stacks, restricted access to machines and so on. All these aspects need to be addressed and while various approaches exist, a common strategy in the field of HPC is still missing.

It is the goal of this project to investigate the different approaches taken by the JLESC HPC centers, to gather own, hands-on experiences with those approaches and to evaluate their pros and cons. The initial focus will be on continuous integration, a later extension to Cx is intended. Further partners are welcome at any time.

Expected contributions:

* Overview of CI solutions for HPC centers and codes
* Best practice guide for teams/centers thinking about employing CI for their HPC machine
* Community building and exchange in the field of RSE and Cx within the JLESC

## Results for 2021/2022
None, the project started in early 2022.

## Visits and meetings
None.

## Impact and publications
None.

{% bibliography --cited --file jlesc.bib %}

## Future plans

Planned results:

* Internal report on existing CI solutions
* White paper/best practice guide on CI for HPC
* Similar results for Cx, if feasible



## References
<!-- {% bibliography --file external/activestorage_project.bib %} -->
