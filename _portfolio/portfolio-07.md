---
title: "Abaqus UEL for beam-to-solid coupling."
excerpt: "Abaqus User Element to embed spatial Timoshenko beams to hyperelastic solid matrices.<br/><img src='/images/P3_AbaqusUEL.png'>"
collection: portfolio
---

In this project, I implement the simplest version of a multi-layered actuator, with only one layer of dielectric elastomer (active region) covered by a stiffer thin layer (passive region).
The actuator is modeled in ABAQUS by implementing a UMAT subroutine. Also, included a (short) sensitivity analysis by examining the effect of stiffness and thickness variations of the thin layer to the overall mechanical response of the actuator. Finally, I examine and model the case of distributed stiffeners along the free surface of the elastomer.

This project was part of the graduate class EM397: Mechanics of Soft Materials (Fall 2019). [PDF](http://sotiriskak.github.io/files/DE_FEModel.pdf)