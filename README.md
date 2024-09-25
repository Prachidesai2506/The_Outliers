# The_Outliers

#### Movement of Single Bot (Movement_single.ipynb) 

This project implements the A* algorithm to determine the shortest path for a single bot moving from a given source to a destination within a grid. The bot's movement is tracked and displayed step by step with directional commands.

##### Key Features:
- The bot starts by facing upward.
   - Movements are printed in a sequence of actions such as:
      - Forward: Move in the current direction.
      - Left: Rotate 90° counterclockwise.
      - Right: Rotate 90° clockwise.
When moving in a different direction (e.g., from facing upward to moving right), the bot first changes its direction (via left or right turns) and then proceeds forward.
By applying the A* algorithm, the bot calculates the optimal path considering obstacles and efficiently reaches its destination.
