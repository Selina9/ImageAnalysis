# ImageAnalysis
Image analysis using python to determine damage caused to DNA after irradiation, using the comet assay method.
The aim here is to automate the process of determining the level of damage that has been caused to cells. Currently, thisanalysis  is performed using the Komet software which requires the user to manually select the comets to be analysed and define the head and tail regions of the comet. This is a long adn laborious task which is a por use of resources.
The code outlined here aims to make this process of damage analysis a more reliable, quantifiable and most importantly much quicker process.
It reads in multiple image files taken of cells after performing a comet assay and outputs arrays. The arrays contain information of every comet that has been analysed, and informs the user of the comet:
- area
- length
- height
- % intensity in the tail

The arrays are then written to file in a spreadsheet for easy manipulation and readability for the user.
Alongside data output, the analysed comet plots are saved to file for ease of reference for the data.

The spreadsheet consists of 4 sheets; area, width, height and tail intensty %.
These measurements are then further split into 2 kinds, good and bad. Good data is that of comets that have been deemed to be correct and not contaminatin or overlap. Bad data is from objects recognised as too large, too small or outside the fiducial region of the image. This allows all the data to be offered to the user, and with reference to the plots that are also output they can perofrm any further analysis required.

