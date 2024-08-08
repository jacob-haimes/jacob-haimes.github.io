---
title: "CPPN2Sim"
date: 2021-11-02
last_mod: 2024-08-07
featured: false
reading_time: false

authors:
  - admin
  - Lawrence Smith

summary: MATLAB library for converting Computational Pattern Producing Networks into lightweight simulations of actuator behavior.

categories:
  - Research
tags:
  - MACLab
  - Repo
  - Simulation and Analysis
  - Visualization
  - Robotics

image:
  caption: 'Actuator visualization used in Stretching the Boundary'
  preview_only: true
  filename: f10-min.jpeg

url_code: 'https://github.com/MacCurdyLab/CPPN2sim'
---

While obtaining my Master's Degree, I collaborated closely with the [MACLab](https://www.matterassembly.org/), a lab located at the University of Colorado's Boulder campus which is led by [Dr. Robert MacCurdy](https://www.colorado.edu/mechanical/robert-maccurdy).

In order to conduct the research which would be presented in the papers <a href="https://jacob-haimes.github.io/PDFs/Smith-Haimes-MacCurdy_Shell-Elements_ROBOSOFT.pdf" target="_blank" rel="noreferrer noopener">Stretching the Boundary</a>  and  <a href="https://jacob-haimes.github.io/maclab/Automated-Synthesis-of-Bending-Pneumatic-Soft-Actuators/" target="_blank" rel="noreferrer noopener">Automated Synthesis of Bending Pneumatic Soft Actuators</a>, we first had to design a seemless pipeline which would take in a Computational Pattern Producing Network (CPPN), generate a corresponding mesh, run some set of simulations using that mesh, and return desired metrics from that simulation.

Our solution was the <a href="https://github.com/MacCurdyLab/CPPN2sim" target="_blank" rel="noreferrer noopener">CPPN2Sim</a> package, which accomplishes this task when used in conjunction with <a href="https://www.mathworks.com/products/matlab.html" target="_blank" rel="noreferrer noopener">Matlab</a>, <a href="https://www.3ds.com/products-services/simulia/products/abaqus/" target="_blank" rel="noreferrer noopener">Abaqus</a>, and <a href="https://www.gibboncode.org" target="_blank" rel="noreferrer noopener">GIBBON</a>.

This package was used heavily for both of the aforementioned conference papers.
