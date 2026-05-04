
# Projectile Motion Simulator (MATLAB)

## Overview
This project is a **projectile motion simulator** built in MATLAB. It allows users to explore how objects move through the air under the influence of gravity by adjusting key variables such as **launch angle** and **initial velocity**.

The goal is to help users visualize and understand projectile motion using calculations and graphical output.

## Authors
- Angie Williams
- Suemin Jung

## Objective
Projectile motion describes the motion of an object launched into the air while gravity pulls it downward. This project helps users understand the relationship between initial velocity, launch angle, distance traveled, maximum height, and total time in the air.

## Features
- User inputs initial velocity and launch angle
- Calculates total distance traveled
- Calculates maximum height reached
- Displays a graph of the projectile path
- Checks that the user enters valid inputs

## Physics Concepts Used
This project uses standard projectile motion equations. Air resistance is neglected, and gravity is assumed to be constant.

The motion is separated into horizontal and vertical components:

```text
x = v0 * cos(theta) * t
y = v0 * sin(theta) * t - (1/2) * g * t^2
```

Where:

```text
v0 = initial velocity
theta = launch angle
t = time
g = gravity, 9.81 m/s^2
```

## MATLAB Concepts Used
This project uses basic MATLAB programming concepts, including:

- Input functions
- Output functions
- Conditional statements
- Loops
- Plotting functions

## How It Works
1. The user enters the initial velocity.
2. The user enters the launch angle.
3. The program separates the velocity into horizontal and vertical components.
4. The program calculates the maximum height, and distance traveled.
5. The program plots the path of the projectile.

## Assumptions
- Air resistance is ignored
- Gravity is constant at 9.81 m/s^2
- The projectile starts at ground level
- Motion occurs in two dimensions

## How to Run
1. Open MATLAB.
2. Open the project script file.
3. Run the script.
4. Enter the requested initial velocity and launch angle.
5. View the calculated results and projectile motion graph.

## Expected Output
The program will display:

- Maximum height reached
- Horizontal distance traveled
- A graph showing the projectileâs motion

## Future Improvements
- Add air resistance
- Add an animation of the projectile
- Allow the user to compare multiple projectiles
- Create a graphical user interface
- Allow different starting heights

## Purpose
The purpose of this project is to help users understand projectile motion while also practicing beginner MATLAB programming skills.
