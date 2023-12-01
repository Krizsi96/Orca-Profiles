# OrcaSlicer Profiles

## Where to put this?

This repo should be cloned to the local OrcaSlicer application data folder. that can be found at...

- on Windows: `C:\Users\<username>\AppData\Roaming\OrcaSlicer\user\<username>`

## How to tune your printer settings

Follow the instructions of `teaching tech` from this [website](https://teachingtechyt.github.io/calibration.html#linadv)

⚠️ For machine calibration (*step 1*) try to not use filament methods (like XYZ calibration with filament), because the can affect the result and your setting will be filament specific. Generalyze it as much as possible and use slicer settings (*step 2*) for compensating the filament behavior (like different flowrate, or shrinkage after printing).

1. **Calibrate the printer in the firmware**

- check the frame and lubricate the moving parts
- tune the temperature PID controllers
- XYZ steps calibration

2. **Calibrate the filaments properties in the slicer**

- tune first layer
- temperature tuning
- slicer flow calibration
- speed & max flow tuning
- acceleration tuning
- retraction tuning
- linear advance

ℹ️ Good way to test the dimensional accuracy is printing the LEGO test object. Print it both in horizontal and vertical position, then check the dimensions and the fitment with original LEGO parts.

## Commit types

The commits to the repository must follow the [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/#specification) style with the following types:

- **new:** the change adds a new profile
- **fix:** the change fixes an existing profile
- **docs:** the change adds or changes the documentation
