# Electron Gun - Scanner

This LabVIEW program controls an electron gun scanner and is compatible with NI-DAQ.

## Requirements
- LabVIEW 20.0 or later
- NI-DAQ

## Installation
1. Ensure you have LabVIEW 20.0 or a later version installed on your computer.
2. Download all the files in the "electron gun system" folder from the repository as a ZIP file.
3. Extract the ZIP file to a desired location on your computer.

## Setup
1. Connect your NI-DAQ to your computer.
2. Connect the following:
   - `a0` to the X-AXIS cursor
   - `a1` to the Y-AXIS cursor

## Usage
1. Open the LabVIEW project file in LabVIEW.
2. Select the desired state for the cursor from the options (constant, spiral, X/Y-constant, or raster).
3. Press the "Start" button to begin the program.
4. To change the cursor's direction, **you must**:
   - Press the "Stop" button.
   - Switch to the appropriate tab.
   - Press the "Start" button again.

### Step and Location Settings
- Each state has specific modifications available: step size and location.
- Before making any modifications, ensure the program is stopped.

## Notes
- Always stop the program before changing settings or switching tabs.

## Author
 Tal Adoni
 Ben Gurion University
