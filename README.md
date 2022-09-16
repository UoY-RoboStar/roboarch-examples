# RoboArch Tool

| Repository                                                                        |        |
| :---                                                                              | :---:  |
| [roboarch-metamodel](https://github.com/UoY-RoboStar/roboarch-metamodel)          |        |
| [roboarch-textual](https://github.com/UoY-RoboStar/roboarch-textual)              |        |
| [roboarch2chart-epsilon](https://github.com/UoY-RoboStar/roboarch2chart-epsilon)  |        |
| [roboarch-examples](https://github.com/UoY-RoboStar/roboarch-examples)            |  <--   |
| [robochart2text-epsilon](https://github.com/UoY-RoboStar/robochart2text-epsilon)  |        |

This is repository contains RoboArch  examples.

## Obstacle Avoidance Case Study
A puck robot that moves through its environment avoiding obstacles. The software architecture of the system has has two layers a control layer and an executive layer. The control layer uses the reactive skills pattern with three skills: Proximity, Explore, and Move. The executive layer uses no pattern and is defined using RoboChart to configure the control layer to explore the environment.


## Obstacle Avoidance Case Study Reduced
A simplified version of the obstacle avoidance case study that has two skills to assist verification of the skills manager by reducing number of states in the generated CSP model.
