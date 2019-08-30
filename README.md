# SLAM-python
Simultaneous localization and mapping also commonly known in short as SLAM written in python.
SLAM is a technique for creating maps and updating those maps based on sensing data and then calculating for uncertainty. In robotics this is a way to track the position of a robotic system.  When faced with a lack of precise sensing data this will help alleviate the robots uncertainty to fully make the robot autonomous such as self-driving cars, unmanned aerial vehicles, autonomous underwater vehicles, rovers, and domestic robots such as cleaning robots. Some of the methods to accurately predict the robots position are Extended Kalman Filter, Maximum a Posteriori (MAP) estimation or Bundle Adjustment (BA).
In this project we gather data from sensing of generated landmarks then calculate it's position in a 2d world. This process is repeated every time we move to have an understanding of the robots localization in this enviroment. Graph SLAM is the method used, it simplifies the estimation by defining the probabilities using a sequence of constraints.  It takes in its initial position and then calculates based on previous poses to a newer pose. 

## Run these files in sequence:

1. Robot Moving and Sensing
2. Omega and Xi, Constraints
3. Landmark Detection and Tracking
