# Warehouse-Robot-Reinforcement-Learning-Project

This project involves creating a custom environment using Gymnasium to simulate a warehouse setting where a robot learns to navigate, pick up, and deliver items efficiently. The robot is trained using Q-learning, a classic reinforcement learning algorithm, to optimize its behavior for warehouse tasks.

https://github.com/user-attachments/assets/09e5cdb4-53c3-49f7-82fb-2f19b3d51d2b

PROJECT DETAILS

Custom Gymnasium Environment:
The warehouse is modeled as a grid world where the robot can move in four directions (up, down, left, right). It interacts with pickup points, delivery spots, and avoids obstacles to complete delivery tasks.

Q-Learning Algorithm:
The agent learns an optimal policy through trial and error, updating its Q-values based on rewards received for successful pickups and deliveries, and penalties for wrong moves or collisions.

Training and Evaluation:
Through multiple episodes, the robot improves its policy to maximize efficiency and minimize task completion time.

Visualization:
The environment includes a visual representation of the robot’s movements and task progress, aiding in understanding and debugging.

REAL-LIFE APPLICATION

Warehouse Automation:
Reinforcement learning agents like this can be used to train robots for logistics automation, improving productivity in warehouses.

Optimizing Robot Navigation:
Algorithms trained in simulation can help robots learn efficient paths and task sequences, adapting to dynamic environments.

Reducing Operational Costs and Enhancing Safety:
Automated robotic systems reduce manual labor needs and improve safety by handling repetitive or hazardous tasks.

This project demonstrates how Gymnasium and Q-learning can be combined to model and solve real-world warehouse logistics problems with reinforcement learning.

CREDIT
This project was completed by following the tutorial series by Johnny Code on YouTube. Huge thanks for the detailed walkthroughs and guidance!
