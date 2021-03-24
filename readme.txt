LabVIEW VIs used in Dual-Trap Optical Tweezers instruments.

The VIs in ./HiRes/ have been written by me (Alex Tong) (though based on an earlier implementation), and control a dual-trap optical tweezer (Design docs at doi:10.1101/pdb.ip73, doi:10.1101/pdb.ip74). In this instrument, the trapping laser is split in two traps (by polarization), and the position of one trap is controlled by a piezoelectric mirror.

The VIs in ./Timeshareds/ are adapted from code written by Matt Comstock(?) with some work/tidying by various people, and control dual-trap optical tweezers (Design doc at doi:10.1007/978-1-4939-6421-5_8). In this instrument, the position of the trapping laser is rapidly (~100kHz) switched between two locations (the positions of the two traps) by an acousto-optic deflector.

Licensed under the GNU GPL v3 license. See COPYING.txt

Last Edited 03 23 2021