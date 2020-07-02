# ETS-VII Manipulator Arm Model

This folder contains the robot manipulator arm model from the Japanese Engineering Test Satellite 7 or more commonly known as ETS-VII.

The publications used for creating the robot model URDF file are as follows:

- The Kinematic Parameters such as link lengths, joint axis, and joint placements were taken from the following paper: K. Yoshida, “Engineering test satellite VII flight experiments for space robot dynamics and control: Theories on laboratory test beds ten years ago, now in orbit,” Int. J. Rob. Res., vol. 22, no. 5, pp. 321–335, 2003.


- The inertial parameters were taken from the following paper: K. Yoshida and S. Abiko, “Inertia parameter identification for a free-flying space robot,” AIAA Guid. Navig. Control Conf. Exhib., no. August, pp. 1–8, 2002.


The inertial parameter estimation paper does not mention the location of the inertial frame in which the inertia tensor is represented in. For the Spacecraft base, this is taken as the center of mass/center. For the link in the manipulator arm, the inertia tensors are given with respect to the link frames.