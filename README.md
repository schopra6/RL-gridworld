# RL-gridworld

![alt text](https://github.com/schopra6/RL-/blob/[branch]/image.jpg?raw=true)

## Problem Statement 

To solve a given Maze, one has to use a sequence of commands that transforms the Pre-grid to Post-grid. The objective is to use small number of commands to solve the task. Figure 1a shows a Karel task with a solution in Figure 1b that uses minimal-sized command sequence.

AVATAR: A Karel AVATAR is characterized by its current location and orientation. Its orientation
can be one of {NORTH, EAST SOUTH, WEST} and its location can be any of the grid-cells. The
blue dart in Figure 1a depicts the location and orientation of the AVATAR. The AVATAR can move
around the grid and is directed via different Karel commands as will be described below.

Description of Karel commands <br />
• move: This moves the AVATAR one grid-cell in the direction it is currently oriented in. If the
AVATAR hits a WALL or the grid-boundary, then the AVATAR “crashes” and the program terminates. <br />
• turnLeft: This orients the AVATAR in the direction left of its current orientation.<br />
• turnRight: This orients the AVATAR in the direction right of its current orientation.<br />
• pickMarker: This removes a MARKER from the current location (grid-cell) of the AVATAR, if present. If no MARKER is present, the AVATAR “crashes” and the program terminates. <br />
• putMarker: This adds a MARKER on the current location (grid-cell) of the AVATAR, if no MARKER is present. If a MARKER is already present, the AVATAR “crashes” and the program terminates. <br />
• finish: This command is sent to the AVATAR to indicate end of a sequence of commands.<br />

