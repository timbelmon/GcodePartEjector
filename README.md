# GcodePartEjector
JS Script that automates the process of Gcode Manipulation. Is used for automatic Print Removal for 3D-Printers.

This Project is still WIP but it is functional. You need to use Gcode made with PrusaSlicer, i've tested it using a Prusa Mk3s and an Ender 3. Both work well depending on the Printhead Offset.
This Script uses known points for figuring out the Gcode, im aware some of these Points have changed with the release of the Mk4 with Input shaping, this will need to be added / adjusted.
I hate CSS and it shows, feel free to improve and PR.

!!! - Extruder Head Offsets will need to be adjusted for each printer. You can find them using Ctrl+F "Extruder Head Offset". You can find out these Values by Measuring your Printhead. - !!!

If youre confused what this code does:
https://www.youtube.com/watch?v=01QJgSK_tZE
