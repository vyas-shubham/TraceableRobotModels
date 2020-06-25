# ETS-VII Manipulator Arm Model

This folder contains the robot manipulator arm model from the Japanese Engineering Test Satellite 7 or more commonly known as ETS-VII.

The publications used for creating the robot model URDF file are as follows:

- The Kinematic Parameters such as link lengths, joint axis, and joint placements were taken from the following paper: K. Yoshida, “Engineering test satellite VII flight experiments for space robot dynamics and control: Theories on laboratory test beds ten years ago, now in orbit,” Int. J. Rob. Res., vol. 22, no. 5, pp. 321–335, 2003.


- The inertial parameters were taken from the following paper: K. Yoshida and S. Abiko, “Inertia parameter identification for a free-flying space robot,” AIAA Guid. Navig. Control Conf. Exhib., no. August, pp. 1–8, 2002.


Since, the inertial parameter estimation paper does not mention the location of CoM of the link, these were taken from the ETS-VII example files of the "Basic Muiltibody Simulator Derived" made by Dr. Dimitar Dimitrov. This can be found at: https://github.com/drdv/bmsd.