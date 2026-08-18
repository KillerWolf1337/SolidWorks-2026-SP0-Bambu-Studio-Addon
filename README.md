# Bambu SolidWorks Add-in

A small SOLIDWORKS 2026 add-in that makes it easier to open models in Bambu Studio.

The add-in adds a Bambu menu to SOLIDWORKS. The active model can be exported as a 3MF file and opened directly in Bambu Studio.

## Features

* Export the active SOLIDWORKS model as a 3MF file
* Open the exported file directly in Bambu Studio
* Automatically detect common Bambu Studio installation paths
* Manually select the Bambu Studio executable
* Choose where exported files are saved
* Save settings automatically

## Requirements

* SOLIDWORKS 2026
* Bambu Studio
* Windows

SOLIDWORKS and Bambu Studio are not included with this project and need to be installed separately.

## Installation

Download the latest release and run the .exe.

After starting SOLIDWORKS, enable **Bambu SolidWorks** under **Tools → Add-Ins**.

The Bambu menu will then be available in SOLIDWORKS.

## Usage

Open and save a SOLIDWORKS part or assembly.

Select:

**Bambu → Export + Bambu Studio**

The add-in exports the active model as a 3MF file and opens the file in Bambu Studio.

The export location can be configured under:

**Bambu → Settings**

If Bambu Studio is not detected automatically, its executable can be selected manually.

## Notes

The SOLIDWORKS document needs to be saved before it can be exported.

The exported 3MF file uses the same filename as the SOLIDWORKS document.

## Disclaimer

This is an independent project and is not affiliated with or endorsed by Dassault Systèmes, SOLIDWORKS, or Bambu Lab.

SOLIDWORKS and Bambu Studio are trademarks of their respective owners.

This project does not include or redistribute SOLIDWORKS, Bambu Studio, or their proprietary files.

## License



All rights to the source code remain with the author.

## Issues

If you find a bug, please open an issue and include your SOLIDWORKS version, Bambu Studio version, Windows version, and a description of the problem.
