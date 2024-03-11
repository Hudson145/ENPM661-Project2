ENPM 661 Project 2: Implementation of Dijkstra algorithm for a Point and Rigid Robot
Heqin Wang

This project showcases the implementation of Dijkstra's Algorithm for solving obstacle maps for both point and rigid robots. It demonstrates pathfinding capabilities in a specified environment, illustrating the algorithm's effectiveness in navigating through obstacles to reach a designated goal.


Setup Requirements

Dependencies:
numpy: For numerical computations and matrix manipulations.
math: For mathematical operations.
heapq: For implementing priority queues.
time: To measure execution times.
cv2 (OpenCV): For image processing tasks.
pygame: For rendering animations.

Getting Started
Point Robot
For the point robot scenario, the program requires the following inputs:

x_start: X-coordinate of the start position
y_start: Y-coordinate of the start position
x_goal: X-coordinate of the goal position
y_goal: Y-coordinate of the goal position
Rigid Robot

In addition to the point robot inputs, the rigid robot scenario also requires:

Radius: The radius of the robot
Clearance: The clearance distance between the robot and obstacles

Execution and Outputs

The solution process takes approximately 5 minutes, depending on the system's specifications. Upon completion, the program will:

Indicate when the goal is reached and start backtracking to the start position.

Display an image showcasing the obstacles within the environment.

Present a Pygame animation illustrating the robot visiting all nodes. Note: The animation is designed for fullscreen. Please allow it to run its course to avoid disrupting the execution.

Conclusion

This project exemplifies the practical application of Dijkstra's Algorithm in robotic pathfinding, providing insightful animations and visual feedback on the algorithm's decision-making process. For further details, questions, or contributions, please contact the authors at their University of Maryland email addresses.

