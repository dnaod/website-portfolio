---
title: "Canada Arm 2's Mobile Base System Payload Orbital Accomodator"
date: 2001-12-28
featured: true
description: "I wrote the software controlling the Payload Orbital Accomodator on the Canada Arm 2's (SSRMS) Mobile Base System"
tags: ["Ada83/Ada95","Unix","6086 assembly"]
image: "/img/mcmbmt_hr.jpg"
link: "https://www.asc-csa.gc.ca/eng/iss/mobile-base/"
fact: "Interesting little tidbit shown below image on summary and detail page"
weight: 500
sitemap:
  priority : 0.8
---
**More detail on its way!**

The Canada Arm 2 project was a robotic arm installed on the International Space Station.  It remains in operation today performing a variety of tasks from loading and unloading cargo modules to assisting extra vehicular activities by astronauts during station maintenance tasks.  MDA was responsible for the command and control software that drove the 3 major pieces of the arm: the Space Station Remote Manipulator System (SSRMS), Mobile Base System (MBS), and Special Purpose Dextrous Manipulator (SPDM but later renamed "Dextre").

I had 3 roles during my tenure at MDA.  I first acted as a test member creating test scripts for our automated test system.  During this time, I led a team of 2 as we enhanced and extended the test suite.  Once a defect was found, we debugged the Ada code to correct the source code and submit the fixes.

I also debugged and validated the self-diagnostic assembly source code written.  I discovered a critical defect which would have corrupted the command and control software completely, leading to a complete shutdown of the arm operations.

Lastly, I wrote the code for a subcomponent of the MBS called the Payload Orbital Accomodator (POA).  This was a docking port on the MBS where the SSRMS could attach payload modules.  Once a payload was attached to the POA, the Power Data Grapple Fixure (PDGF) would apply power and data to the payload for the collection of sensor data and application of heating - protecting the payload from the brutal space environment.

![A picture of the Canada Arm 2 with a portion of Earth in the background](/img/CanadaArm2.jpg)