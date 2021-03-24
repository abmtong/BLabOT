Readme for Code and Software Submission Checklist for 'A DNA packaging motor inchworms along one strand allowing it to adapt to alternative double-helical structures'

System Requirements:
 LabVIEW : Code was written and run on v8.1. Compatability with newer versions of LabVIEW is presumed but not guaranteed.
 Optical Tweezers: The instrument should be built to the specifications in doi:10.1101/pdb.ip73 and doi:10.1101/pdb.ip74 .
 Connections to PC: The NI DAQ card should be named "Dev1" in NI MAX, and the connection order for the position-sensitive detectors and the piezo mirror is: [Trap A - Y direction, Trap B - Y direction, Trap A - X direction, Trap B - X direction, Piezo Mirror - X Position , Piezo Mirror - Y Position, Trap A - Sum , Trap B - Sum]. The sample chamber's position is controlled by an ESP300 motion controller and is connected as COM1, and has a trackball attached to the ESP300's GPIO slot. The trap A and B shutters are connected to the NI DAQ card through DIO0 and DIO3, respectively.

Installation guide:
 Unzip the code. Only ./HiRes/CurrentVIs/ is needed.

Instructions for usage:
 Run ./HiRes/CurrentVIs/MainV8.vi . Everything is done in that VI.

There are prohibitively many details to go into here, only the gist has been covered. The VI front panels and block diagrams are hopefully comprehensive enough to understand, otherwise contact me (Alex Tong) or the Bustamante Lab.
