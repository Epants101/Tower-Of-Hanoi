# Tower-Of-Hanoi
An implementation of the Tower of Hanoi logic puzzle in c++.

BUILD INSTRUCTIONS
If you are on Windows, a prebuilt binary is present in the root directory of the repository.
Otherwise, premake must be used to build the project. On Windows, run premake.bat, then build the visual studio project.
On another platform, the build must be done manually through the command line.

USAGE
Click on one rod, then another to move the top disk on the first rod to the second, if the move is legal. 
The r key can be used to reset the puzzle. 
The s key can be used to save screenshots, however, the directory it saves to is hardwired into the code.
Likewise, the number of disks is hardwired into the code. It would need to be recompiled to change either setting.
