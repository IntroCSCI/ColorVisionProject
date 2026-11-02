# Color Contrast Grader

### Developed for CSCI-111 by Jaz Salazar.

## Description

### **Version 1.4**

This program compares two colors to determine a measurement of contrast and evaluate it according to WCAG 2.x standards.

### New in v1.4:
 - Replaced basic contrast calculation with a more advanced version to calculate contrast using luminance-normalized colors; based on WCAG 2.x.

### New in v1.3:
 - Support for HEX input!
 - Refactored input validation for more advanced RGB and HEX validation.
 - More robust error output.
 - MISC fixes.

### To be added in v2.x:
 - Support for color blindness conditions evaluation.

## Example Output:
```
This program will evaluate two colors based on WCAG 2.x.
RGB colors must be three integers separated by whitespaces and between 0-255.
HEX colors must be in six digit format (optionally with '#' or '0x' prefixes).
Examples: '157 34 53', '0 0 0', '0x9D2235', '#75787b'

Enter color values in RGB or HEX format for Color 1 of 2:
123 4 255

Enter color values in RGB or HEX format for Color 2 of 2:
255 255 255

You have selected the following colors: 123 4 255 and 255 255 255
Contrast Ratio: 6.35678:1

These colors have a decent amount of contrast.

Process finished with exit code 0
```
