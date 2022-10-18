# PAC-MAN-in-python
An attempt at recreating pac-man in python using [pacmancode.com](https://pacmancode.com/) as a guide.

Current Status of the Project:
Fully playable with properly rendered maze, working score counter and animations with all basic functions of the original PAC-MAN successfully recreated.
 
To run the game press SPACEBAR on the keyboard and use ARROW KEYS to move PAC-MAN through the maze.
 
The goal of the game is to eat all the PELLETS and score as much points as possible while avoiding the ghosts. The PAC-MANS at the bottom indicate the number of lives you have left.
 
When PAC-MAN eats the large pellet called as POWERPELLLET the ghosts turn blue and can be eaten giving more points.

Maze: the text file contains the layout of the maze, NumPy is used to load the text file and nodes are created at all the ‘+’ each node also contains directions of adjacent connected nodes. A path is created between the nodes and entities (PAC-MAN, Ghosts) move along the path.
