# SophieWallace_POC_Contents


# Background:


This repository contains the Proof of Concept (POC) Implementation task for FOAR705. This POC contains a workflow to export photos from Mac's default photo application into Tropy with additional metadata. This aims to demonstrate a more streamlined process for qualitative researchers in the field who want their photographic data to be more organised, detailed, managed and stored efficiently.


# Outline:


# Requirements:
This can only be run on a macOS Catalina. It cannot be run on Windows.

This needs the application Automator. This is a default application in macOS Catalina and is required.

The application Tropy needs to be downloaded from [Tropy.org](https://tropy.org/download/mac)

The application Duplicati needs to be downloaded from [Duplicati](https://updates.duplicati.com/beta/duplicati-2.0.4.23_beta_2019-07-14.dmg)

The application Github Desktop needs to be downloaded from [Github](https://central.github.com/deployments/desktop/desktop/latest/darwin)

The application Automator can be viewed in more detail in the [Automator User Guide](https://support.apple.com/en-au/guide/automator/welcome/mac)

# Installation:


* Download Tropy and Duplicati applications from link above.
* Clone this repository to your computer using github desktop. It is important that the file Exiftool_Script is in folder asdfasdf
* Create folder named "Export" in default Mac Photos application
* Move the images from the repository into the newly created "Export" folder in Mac photos



# Testing The Workflow

* Run POC_Automation workflow
* Promp for writing location should appear
* Write location metadata for the photos, in this case "Changu Narayan"
* Tropy interface appears and tropy_input images appear in finder
* Drag photos from tropy_input folder into Tropy 
* Photos should appear in Tropy with metadata including creator, original date and time and location under 'type' column.


# Issues:

**Automator**
* Utilising key commands such as "command A" crashed the application. 
* Actions such as renaming folders, work haphazardly.
* Actions are extremely limited 
* Actions focus predominantely on Mac applications
* Only available on macOS Catalina.

**Tropy**
* Tropy does not work with the command line
* Tropy does not accept diverse data
* Tropy does not work with Mac default photos application
