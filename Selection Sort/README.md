# Selection Sort

![logo](https://github.com/jamesrussellt/Ball-Machine/blob/master/Images/Selection_Assy.png)

This folder contains the CAD models and manufacturing drawings required to make a selection sort comparator.

See folders `Selection - X Lanes` for copies of the design for the required number of ball lanes.

## How it works
The comparator is required to select and remove the heaviest ball as per the selection sort algorithm.

It comprises of 4 sections:
 * Timing Gate
 * Ramps
 * Selection Shaft
 * Reset mechanism
 
`Timing Gate`
 * To release all balls at the same time (see `Timing Gate` folder).
 
`Ramps`
* To allow the heaviest ball to roll to the bottom the quickest and separate it from the other balls (this design has been proven not to work and as such requires a design update and further prototyping work to complete - see `Prototype CAD` folder).
 
`Selection Shaft`
* The first ball down the ramps rotates the shaft and falls into the first set of tubes. The shaft is caught by a catch lever on the outer left hand side and the other balls roll over the top of the shaft into the other set of tubes. This separates the heaviest ball from the rest of the pack.

`Reset mechanism`
* For multiple uses of the machine, the reset mechanism releases the catch lever when the next set of balls pass the timing gate. A counterweight on the outer right hand side of the machine lifts the Selection shaft back into position.
