frc-java-emulator
=================

This is a version intended for use by team 3328.  All credit for the original code belongs to SouthEugeneRoboticsTeam where this repo was cloned from and the GPL licence included still applies.

Simple Emulation package for FIRST Robotics Java code running on a cRio

1. Add the frc-java-emulator jar to your build path

2. Make sure that you also have frc-java-emulator's dependencies, Reflections and Javassist.

3. Change all your WPILib imports to robotemulator ones (either add "import robotemulator.*;" or do a find and replace for "edu.wpi.first.wpilibj" with "robotemulator")

4. Run the code! The main class is "robotemulator.RobotEmulator".  It will search for all classes extending IterativeRobot and ask which one you want to run. 
