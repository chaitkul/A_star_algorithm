# a_star_phase02_ED
A star algorithm implementation for 2D map

Libraries used for 2D visualization:
1. import numpy as np
2. import math
3. import heapq
4. import cv2

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Steps to run the code for 2D visualization:

1. Open any IDE and run the source code (.py) file.

2. You will be prompted with a user interface at the terminal:
			1. Enter the clearance value (in cm). For best results enter clearance between 1 and 10.
			2. Enter the start coordinates (in cm) and theta.
			3. Enter the goal coordinates(in cm).
			4. Enter the rpm1 and rpm2 values. For best results enter rpm values above 50.
			
3. The canvas will be prompted and robot will start exploring the nodes, the explored nodes are shown with green color and the shortest path is shown with pink color.

4. After the robot reaches the goal node, it will plot the shortest path.

5. Finally, the path and total cost from start node to goal node is being printed.
