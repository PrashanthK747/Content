
# Drone Height Control

The `Drone_height_control.m` file is a comprehensive MATLAB script that contains the altitude dynamics of a drone with a control algorithm. The `Drone_height_control.m` file combines everything into one script to make it easier to understand and run.

## Overview

  - ### Dynamics
    Using newton's second law the drone 1-D equation of motion of the drone
    - $` F = F_{control}-F_{gravity} `$
    - $` ma_{z} = F_{control} -mg `$
  - ### Control algorithm
    - $` F_{control} = mass*(gravity + Kp(h_{d}-h)+Kd(\dot{h}_{d}-\dot{h}))`$
        - where
        - Kp propotional control gain
        - Kd derivative control gain
        - h_{d} desired height
        - h actual height
        - $\dot{h}_{d}$ desired velocity
        - $\dot{h}$ actual velocity

## Usage

1. **Download the File:**
   Clone the repository or download the `Drone_height_control.m`
2. **Open and Run:**
   Open the file in matlab and run the matlab code.
3. **Version:**
   Matlab Version - 2023a  

   


