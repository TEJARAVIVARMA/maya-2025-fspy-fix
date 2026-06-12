# Unofficial fSpy Importer for Maya 2025

This is an unofficial update to the original maya_fspy script, modified to work with Maya 2025's new Qt6 UI framework (PySide6).

## Installation & Requirements

Because Maya 2025 no longer includes PyMEL by default, you **must** install it manually before running this script.

**1. Install PyMEL:**
Open Command Prompt as Administrator and run the following commands (adjust the path if you installed Maya on a different drive):
`cd "C:\Program Files\Autodesk\Maya2025\bin"`
`mayapy -m pip install pymel`

**2. Install the Script:**
* Place the `maya_fspy` folder into your Maya scripts directory: `Documents\maya\2025\scripts\`
* (Add whatever command they need to run in Maya to launch it here)
