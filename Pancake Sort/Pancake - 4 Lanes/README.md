# Pancake Sort - 4 Lanes

![logo](https://github.com/jamesrussellt/Ball-Machine/blob/master/Images/Pancake_Assy_4_Lanes.png)

This folder contains CAD models and drawings for the `Pancake Sort` comparator.

## How it works

This comparator uses the `Selection Sort` comparator before it to identify the heaviest ball and pass the balls into the corresponding `Pancake Sort` comparator entry tubes.

 * Each ball lane has two entry tubes (hence 10 entry tubes for 5 ball lanes) - Left for the lighter balls, Right for the heavier balls.

The `Pancake Sort` comparator flips the order of the heaviest ball and the balls to the left of it (just like flipping the largest pancake and all of the others on top of it). The balls to the right of the heaviest stay in lane. The tubes connecting the `Pancake Sort` comparator to the next line of the algorithm are connected so that the full sequence is flipped (the last stage of the Pancake Sort algorithm).

 * The heaviest ball hits a purple lever upon entry which changes the lane directions of the balls to the right of it.
 * These balls pass under the `Z` shaped ball run and into the exit timing gate.
 * The heaviest ball and the balls to the left pass into the `Z` shaped ball run.
 * This keeps the order of the balls the same as they pass into the exit timing gate.
 * The exit timing gate reverses the order of the entering balls as the first drops into place, the others pass over the top.
 * The balls are released out of the comparator at the same time for visual effect to watch the balls flip order as they pass through the connecting tubes (not shown in picture).
