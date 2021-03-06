---
layout: default
title: Deconstruct Speed Data
nav_order: 3
parent: Action Deconstructors
grand_parent: Deconstruct Components
---

# **{{page.title}}**

## **Description**

[**Deconstruct**]({{ site.baseurl }}{% link docs/Deconstruct/index.md %})**:** 
Deconstructs a [Speed Data]({{ site.baseurl }}{% link docs/Parameters/Actions/Speed Data.md %}) into its parameters.

## **Input Parameters**

[**Speed Data**]({{ site.baseurl }}{% link docs/Parameters/Actions/Speed Data.md %}) **(SD):** Defines the [Speed Data]({{ site.baseurl }}{% link docs/Parameters/Actions/Speed Data.md %}) to be deconstructed.

## **Output Parameters**

**Name (N):** Contains the variable name of the deconstructed speed data.

**TCP Velocity (vTCP):** Contains the TCP moving velocity of the deconstructed speed data.

**ORI Velocity (vORI):** Contains the reorientation velocity of the robot tool of the deconstructed speed data.

**LEAX Velocity (vLEAX):** Contains the linear external axes moving velocity of the deconstructed speed data.

**REAX Velocity (vREAX):** Contains the external axes reorientation velocity of the deconstructed speed data.