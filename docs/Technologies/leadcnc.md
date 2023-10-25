---
layout: default
title: Open Builds Lead CNC
nav_exclude: true
has_children: false
permalink: /docs/technologies/leadcnc
---

# OpenBuilds LEAD CNC 1010

## Location
Main Lab, PCA131.

## Technical Details

CNC Desktop Fabrication  
**Model:** LEAD CNC 1010 
**Brand:** Openbuilds 

Travel (Work Area)
X Axis 29" (730mm) / Y Axis 32" (810mm) / Z Axis 4" (~100mm)
Workable Material Height
2" (~47mm) Based on a 1/2" spoiler board stack
Drive System:
Lead Screw Driven
Machine Accuracy
0.001"~0.003" (0.05mm~0.10mm)
Footprint
Lenght/Width 45" x 45" (1148mm x 1148mm) - Height 21" (550mm)

## Setting up CNC software on your computer (Openbuilds)

CNC Software Overview: [Here](https://docs.openbuilds.com/doku.php?id=docs:software:overview)

1. Download and install [Openbuilds Control](https://software.openbuilds.com/)

[Openbuilds](assets\images\OpenBuilds LEAD 1010 00.JPG)
   
2. Once Openbuilds Control is installed, the configuration menu may pop up. If it doesn't, manually open it by going to Configuration --> Configuration Wizard in the top bar.
   
[Openbuilds](assets\images\OpenBuilds LEAD 1010 01.gif)

3. Go to[Openbuilds CAM](https://cam.openbuilds.com/) This is an online platform for generating your G-code. [Follow the instructions here for Setup.](https://docs.openbuilds.com/doku.php?id=docs:software:openbuilds-cam) When setting the controller at step 3, use Spark Concepts xPro for the __Controller__ and __OpenBuilds LEAD 1010__ for the Machine. Then Save. 
[OpenBuild Control Software](https://software.openbuilds.com)



{: .fs-6 .fw-300 }

## Setting up a file with Inkscape
1. Download [Inkscape](https://inkscape.org)
2. Once in the application, set up the work area:
   
  File > Document properties > In here, you can change the units and dimensions of the page

### Create a toolpath

1. Draw the toolpath on the page, or export it from another program (E.g. Illustrator)

- If you're using a solid shape (object) as the base of the toolpath, set the fill to none and the stroke to black. To do this, right click the colors on the bottom left corner and seect the appropriate option.
  To convert to a path: Select shape > Path... > Object to path

### Using Gcodetools to import toolpath

1. Set up Gcodetools properties

  Extensions > Gcodetools > Orientation points...  
  2 Point mode orientation style  
  Z surface: 0.00  
  Z Depth: -1.00 (You can extend these to give the tool more tolerance)  
- Points of reference will pop up at the bottom of the page

2. Save toolpath as a Gcode File

  Extensions > Gcodetools > Path to Gcode...  
  Cutting order: Subpath to subpath.  
- Options tab  
  Scale along Z axis: 1.00  
  Offset alonf Z axis: 0.00
- Preferences tab  
  Here's where you can change the name and location of the file  
- Click apply to save file on computer

A screen will pop up within the Inkscape file that will allow you to make more specific changes 

3. Open Gcode File on the OpenBuild Control Software

In here you can see/simulate the movement of the CNC machine. On the top bar you will also find options to start/pause the job.  
Once the file is imported, make sure you unlock it by clicking on the "unlock alarm"  
Set the 0,0,0 points to create the origin 
  
  


   
   
