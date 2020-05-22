---
layout: default
title: Action Speed Data
nav_order: 1
parent: Code Generation Components
grand_parent: Robot Components Categories
has_toc: false
---

# **{{page.title}}**

## **Description**

[**Code Generation**]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/index.md %})**:** Defines a speed data for a [Action: Movement]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/Action Movement.md %}) or [Action: Absolute Joint Movement]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/Action Absolute Joint Movement.md %}) instruction. Speed data is used to specify the velocity at which both the robot and the external axes move. 

## **Input Parameters**

**Name (N):** Defines the name of the speed data based on a string value. Each speed data name needs to be unique. The first letter shouldn’t be a number. Don’t use special characters.

**TCP Velocity (vTCP):** Defines the velocity velocity of the tool center point (TCP) in mm/s as a number value.

**ORI Velocity (vORI):** Defines the reorientation velocity of the robot tool in degrees/s as a number value.

**LEAX Velocity (vLEAX):** Defines the linear external axes velocity in mm/s as a number value.

**REAX Velocity (vREAX):** Defines the external axes reorientation velocity in degrees/s as a number value.

## **Output Parameters**

**Speed Data (SD):** Contains the Speed Data instructions as action for a [Action: Movement]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/Action Movement.md %}) or [Action: Absolute Joint Movement]({{ site.baseurl }}{link docs/Robot Components/Code Generation/Action Absolute Joint Movement.md %}) instruction.

## **Menu Items**

Through the right-click menu of the component the following options are available:

**Documentation:** Opens the documentation page of the component in your browser.

## **Usage**

[**Code Generation**]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/index.md %})**:** Plug the Speed Data output of this component into the Speed Data input of the [Action: Movement]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/Action Movement.md %}) or [Action: Absolute Joint Movement]({{ site.baseurl }}{% link docs/Robot Components/Code Generation/Action Absolute Joint Movement.md %}) component to set the speed behavior of a robot movement instruction in the RAPID Main Code. This will also add a speeddata variable to the RAPID Main Code.