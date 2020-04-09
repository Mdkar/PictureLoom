# PictureLoom
 Java program to make any photograph into a circular loom design using Processing

**Instructions:**
* Install Java if it is not already installed
* Download and Run PictureLoom.jar
* Set the loom properties (optional)
* Click 'Load Image' to pick an image to loom
* Click 'Load File' to load a previously started loom (need both the .txt and image file)

**Loom Properties:**
The default loom properties are OK for giving decent images in a managable time in general, but can be tweaked for better quality or performance.

Number of Pegs
* This is the number of pegs that are around the circular loom. The more pegs, the finer the resolution. Making this an even number may cause the program to crash.

Minimum Gap
* The program skips this many pegs on both sides of the current peg when picking the next peg to tie the string to

Max Moves
* This is how many strings the program will weave (unless paused or stopped early)

Line Weight
* This is how "thick" the string is. It is actually a measure of opacity (0-255).

