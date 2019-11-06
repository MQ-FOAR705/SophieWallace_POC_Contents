# SophieWallace_POC_Contents


# Background:


This repository contains the Proof of Concept (POC) Implementation task for FOAR705. This POC contains a workflow to export photos from an iPhone into Tropy with additional metadata. This aims to demonstrate a more streamlined process for qualitative researchers in the field who want their photo data to be more organised, managed and stored efficiently.


# Outline:


# Requirements:
This can only be run on a macOS Catalina. It cannot be run on Windows.

This needs the application Automator. This is a default application in macOS Catalina and is required.

The application Tropy needs to be downloaded from [Tropy.org](https://tropy.org/download/mac)

The application Duplicati needs to be downloaded from [Duplicati](https://updates.duplicati.com/beta/duplicati-2.0.4.23_beta_2019-07-14.dmg)

The application Automator can be viewed in more detail in the [Automator User Guide](https://support.apple.com/en-au/guide/automator/welcome/mac)

# Installation:


* Download Tropy and Duplicati applications from link above.
* Clone this repository to your computer using github desktop. It is important that the file Exiftool_Script is in folder asdfasdf
* Create folder named "Export" in default Mac Photos application
* Move the images from the repository into the newly created "Export" folder in Mac photos



# Testing The Workflow

* Run automator
* When prompt appears, write location metadata for the photos. In this case *"Changu Narayan"
* Drag photos from tropy_input folder into Tropy 

# Issues:

* Both the application Tropy and Automator encountered many issues. 
