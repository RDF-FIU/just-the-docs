---
layout: default
title: Bambu
nav_exclude: true
has_children: false
permalink: /docs/technologies/bambu
---

# Bambu 3D Printer

## Location

Main Lab, 3 printers

## Technical Details

3D Carbon Printer - With AMS (Automatic Material System).  
**Model:** Bambu Lab X-1 Carbon combo 3D printer.  
Fused Deposition Modeling.  
**Brand:** Bambu Lab.  
**Supported Filaments:** PLA, PETG, TPU, ABS, ASA, PET.  
**Build plate surfaces:** Bambu cool plate, Bambu engineering plate.  
**Software:** [Bambu Studio](https://bambulab.com/en/download/studio). Third party slicers (Prusaslicer, Cura) are also supported, but some features may
not be available.  

Official Handbook can be found [Here](https://wiki.bambulab.com/en/x1/manual/x1cc-quick-start-guide)

## Setting up the 3D Printing Software
- Make sure to download [Bambu Studio](https://bambulab.com/en/download/studio)
1. Select Login Region - In this case It's North America  
2. Printer Selection - Bambu Lab X1 Carbon, 4.0mm nozzle  
3. Filament Selection - You can choose as many as you'd like to be listed, on the lab we usually work with PLA and PETG

## Step-By-Step Printing Guides
1. Log into the Lab account, ask a manager for the credentials. This will give you access to the print history.
2. Click on **New Project**  
3. On the top menu bar, click on the cube icon with a + sign to import the model. Supported files include .3mf .stl .stp .step .amf .obj  
4. Now it's time to select the Printer/Filament/Process presets
   - The printer dropdown menu should only givde you one option, the Bambu Lab X1 Carbon, 4.0mm nozzle
   - From the printer dropdown menu, select the appropriate one. If there are filaments already loaded onto the printer, the presets should come up automatically.
   - In the process dropdown you are able to choose the layer height. 0.20mm is standard, the smaller the layer height the longer the print will take.  
   ![Presets list](https://github.com/Porti032/labwiki/blob/465fcdca0c962af0ec3bf68d1be9bfb38244e479/assets/images/Bambu%20Presets.png "Presets list")
5. Click on the green "slice" button at the top right hand to generate a .3mf file.
6. This will take you to the preview pane. In here you'll be able to see how the model will look when it's printed as well as the printing times for each parameter.
7. When you're ready, click print on the top right hand corner. This will prompt up a window with a preview of the model plus a list of the printers available
On the lab they are arranged from left to right: Bambu 001, Bambu 002, Bambu 003.
   ![Send To Print](https://github.com/Porti032/labwiki/blob/8f52e7d0d0bb992545008aa95f653d6dcc580b3f/assets/images/Bambu_SendPrint.png "Send Print")


## Loading the filament with AMS
- The AMS is located at above the printers, it can hold up to 4 rolls of filament.  
1. Open up the cover of the AMS and load the spool in slot 1. Grab the filament and push it gently into the grey tab in front of the spool. The AMS will
detect it automatically and start the loading procedure, when this happens you can let go of the filament.  
2. When using an official Bambulab filament spool, the information (type and color) will be filled in the touchscreen.  
   ![Filament menu](https://github.com/Porti032/labwiki/blob/4179fa0f28b39951fdcde3818bd4fb55400cebf2/assets/images/Bambu%20Filament%20Menu.png "Filament menu")
4. For other types of filaments you will have to manually fill the information on the touchscreen. 

## Unloading the filament with AMS
1. On the touchscreen touch "unload" to begin the process.
   ![Unload Filament](https://github.com/Porti032/labwiki/blob/ca5f576cfebaff735dac2c7f801b984b228ef5d5/assets/images/Bambu_UnloadFilament.png "Unload Filament")
3. Open the cover of the AMS and gently pull out the filament by hand.  

## Preparing the Bed
1. Take the bed out and check for any debris. Clean them with the scraper.
2. Apply the glue and put it back on.
- Make sure the magnets of the bed align with the printer.
- If the bed has adhesion problems, make sure you clean it with water and soap, and apply the glue again.


## Features

### Remote Control
Going to the device panel on the Bambu Lab software will allow you to control and monitor the print in real time. You can also watch a live feed remotely from the camera 
installed inside the printer.
