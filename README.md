# MK2 Clone r2 - 3D Printer

In this repository you will find:
 * frame cut drawing (to be cut from 10mm width material, eg. plywood)
 * printed parts needed
 * [bill of materials](bill-of-materials.md)
 * printing profiles for Slic3r PE
 * Customized Marlin 1.1.8 (changelog below)
 
##### Assembly guide
https://mk2clone.dozuki.com/c/MK2Clone_r2_assembly_guide

##### Changes in Marlin
 * Configuration premade files for MK2Clone r2
 * Calibration menu
   * Calibration of Z axis by moving to top
   * Automated UBL - G29 P1, P2 with manual measurement (if needed) and save mesh
 * Filament change without parking when not printing (not working properl right now)
 * Instant moves from LCD move menu (when using high manual move speeds this causes missing steps)
 * Automatically enter move by 1mm instead of choosing 10/1/0.1mm
 * Quick access to Z move by doubleclick while on status
 * Quick access to Z offset adjustment while printing - new position on top of main menu
 
All of those can be disabled/enabled by options in Configuration_adv.

##### More informations
https://prusaclone.wordpress.com/

