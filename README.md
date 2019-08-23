## Overview

Simulated differential drive platform for testing purposes.

## Main steps to set-up a simulated robot

1. Description package: formal geometric description at .xacro file

1. Description package: add inertial tag at links and limit and dynamics tags at joints

1. Description package: For each joint, add a corresponding transmission tag

1. Gazebo package: description extensions at .gazebo file for each link described at xacro file

1. Gazebo package: gazebo plugins, to compute and expose simulated sensors, actuated joints and ground truth.

1. Gazebo package: world model edition

1. Control package, to add control to the actuated joints
