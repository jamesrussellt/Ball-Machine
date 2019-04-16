# Ball-Sorting-Machine
University of Bath - Final Year Mechanical Engineering Masters Project

For exhibition and educational purposes.

![logo](https://github.com/jamesrussellt/Ball-Machine/blob/master/Images/Top_Assy.png)

## About this repository
As part of IMAGINARY open mathematics exhibitions (https://imaginary.org/), this machine demonstrates the use of Selection Sorting and Pancake Sorting Algorithms using balls of different weights.

## Selection Sorting Algorithm
This simple algorithm demonstrates the concept of sorting algorithms by least number of ball comparisons.

This algorithm picks the heaviest ball from the set of balls and places it to the right hand side of the pack. It will repeat this for the remaining balls until all balls have been sorted into weight order.

## Pancake Sorting Algorithm
This more complex algorithm demonstrates the concept of sorting algorithms by least number of reversals or 'flips'. You are more limited in this case than Selection Sort because you cannot simply pick the ball out of the pack and place it at the side.

Imagine you have a stack of pancakes of various sizes which you want in size order with the largest pancake (or heaviest ball in our case) at the bottom. You can only use your spatula to insert under the largest pancake and flip it, with any pancakes above it, so that the largest pancake rests on top of the pile. Then you re-insert your spatula at the bottom of the pile to flip all the pancakes at once so the largest pancake is now at the bottom of the pile. This method is repeated until all pancakes are in size order.

## How the machine works
The machine is effectively a repeat of a few sub assemblies which comprise the first line of the two algorithms. For each following line of both algorithms, the assemblies used are the same but adapted for one less ball lane.

A lever which can be seen towards the bottom right of the image above allows the user to switch between the two algorithms. For Selection Sort, the pancake comparator is skipped and the balls travel around it to the next selection comparator. For Pancake Sort, the balls travel straight from the selection comparator into the pancake comparator.

See `Pancake Sort` and `Selection Sort` for more information on how these comparators work to implement the two algorithms set out above.

## Contents

* `All Drawing PDFs`
  * All PDF manufacturing drawings for reference.
  * Drawings are also included in each sub-folder to show where they are used.
* `Top Level`
  * Machine full assembly.
  * Folder contains CAD models and manufacturing drawings.
* `Balls`
  * Balls of various weights required for the machine.
  * Folder contains CAD models and manufacturing drawings.
* `Pancake Sort`
  * Pancake Sort comparing mechanism.
  * Folder contains CAD models and manufacturing drawings.
* `Selection Sort`
  * Selection Sort comparing mechanism.
  * Folder contains CAD models and manufacturing drawings.
* `Timing Gate`
  * Timing Gate used for Selection Sort comparing mechanism.
  * Folder contains CAD models and manufacturing drawings.

The following folders were used for the creation of the machine and serve no purpose for manufacturing.

* `2018_Templates` 
  * Manufacturing drawing templates used when creating machine assembly and component drawings.
* `Images`
  * Images used for open source documentation.
* `Man`
  * CAD model of human used to present machine size.
* `OldVersions`
  * A backup of old overwritten files automatically saved when using Autodesk Inventor Software.
* `Prototype CAD`
  * A copy of the 'Selection Sort comparator' used to prove design principles.
  * Is built for larger 40mm balls and may contain other components for design adaptation.

## Manufacturing This Machine
Please see `BOM.xlsx` for full list of sub assemblies and parts required for this machine build.
Please see `All Drawing PDFs` for all manufacture drawings.

## Instructions 
See each folder for more detail.

## More info
Another comparing mechanism, designed by Evgeniy Shiryaev, can be used for sorting algorithms which require 2 balls to be compared at a time. This comparator was used as a starting point for the project and lead to the development of Selection and Pancake comparators which compare all balls at once.
See https://imaginary.org/hands-on/balls-sorting-mechanism

## Refer to this work
Cite as: James Taylor. (2019, March 28). jamesrussellt/Ball-Machine




