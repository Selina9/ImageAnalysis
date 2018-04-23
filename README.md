# ImageAnalysis
Image analysis using python to determine damage caused to DNA after irradiation, using the comet assay method.
The aim here is to automate the process of determining the level of damage that has been caused to cells. Currently, thisanalysis  is performed using the Komet software which requires the user to manually select the comets to be analysed and define the head and tail regions of the comet. This is a long adn laborious task which is a por use of resources.
The code outlined here aims to make this process of damage analysis a more reliable, quantifiable and most importantly much quicker process.
It reads in multiple image files taken of cells after performing a comet assay and outputs arrays. The arrays contain information of every comet that has been analysed, and informs the user of the comet:
- area
- length
- height
- % intensity in the tail

