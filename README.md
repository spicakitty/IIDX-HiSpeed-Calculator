# IIDX Hi-Speed Calculator: Python version

This repository contains the Python CLI version of the IIDX Hi-Speed Calculator  
These versions of the tool were originally developed in 2023 from January to September with irregular updates.  
The older versions of the tool can be viewed in older commits.  

The Java version of this tool can be found here &#8594; [IIDX-HiSpeed-Calculator-JavaVersion](https://github.com/spicakitty/IIDX-HiSpeed-Calculator-JavaVersion)

The HTML version of this tool can be found here &#8594; [IIDX-HiSpeed-Calculator-HTMLVersion](https://github.com/spicakitty/IIDX-HiSpeed-Calculator-HTMLVersion)
  
## How to use  
Run the Python script like you would any other Python script.  
## What are these values
- GN (Green Number) is the amount of milliseconds that a note stays on the screen for.
- WN (White Number) is the amount of the screen that is obscured by SUDDEN+ (out of a 1000)
- Screen Limits are WN values that are equivalent to the edge of your TV screen. The values present in this archive correspond to the values I approximated on my CRT TV.

## Version History
### VERSION 1.0  
- Last modified: January 31st, 2023  
- The initial version of the tool.  

### VERSION 1.1
- Last modified: January 31st, 2023  
- Changed some screenlimits values  
- Now rounds WN down to the nearest value available in the games.  
- Adds the option to omit outputs with GNs lower than the input.  
- Adds the option to highlight the output line with the highest speed that is still below the GN limit.  

### VERSION 2.0
- Last modified: February 4th, 2023
- Tool now checks for invalid inputs.
- Changed a screenlimits value.
- Tool now stores default GN values.
- Added a menu option to toggle above values.
- Added a Settings menu to change GN values and other options.
- NOTE: Up until this version, I had been fixing a typo in the code before adding them to this archive. However, I had forgotten to do that when adding this version. As such, the commit to view this version is not "Added v2 to archive" and is instead "Fixed typo in v2". For transparency's sake, the typo was originally fixed between v2 and v3.

### VERSION 3.0
- Last modified: August 20th, 2023
- Changed a lot of the code to use objects instead of arrays of tuples.
- Fixed a typo as mentioned above
- Added option to toggle screenlimits

### VERSION 3.1
- Last modified: September 1st 2023
- Last Python CLI version.
- WN display now calculates and round instead of bisecting a huge array.
- Added padding to the Hi-Speed display.
