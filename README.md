### Interplanetary Voyage Simulation Game

## Objectives

This project aims to exercise the fundamentals of Computer Architecture, specifically assembly language programming, peripherals, and interrupts.

In the coming decades, humanity will continue exploring the solar system, sending astronauts to places never visited before. The objective of this project is to develop a simulation game representing the interplanetary journey of a spacecraft manned by courageous astronauts. Their mission takes them beyond Mars, requiring them to navigate through the asteroid belt between the orbits of Mars and Jupiter.

This region is highly dangerous due to the vast number of asteroids, making collision avoidance crucial for survival. The spacecraft can launch a probe equipped with a missile to destroy an asteroid, but this consumes valuable energy. However, some asteroids contain valuable metals and compounds that can be mined by a robotic unit deployed from the spacecraft, replenishing the energy required for ion thrusters.

## Game Interface

The game interface consists of:
- A screen displaying the gameplay and relevant information.
- A keyboard for control and navigation.
- A set of displays showing the spacecraft's energy levels.

The **MediaCenter module** of the simulator provides various multimedia capabilities, such as setting background images, playing sounds and videos, rendering multiple image layers, and displaying text overlays. Laboratory guide 4 provides further details about this module.

The keyboard allows users to control the game by pressing specific keys to **start, pause, and stop** the simulation, as well as to launch probes for either asteroid destruction or resource mining to replenish the spacecraft’s energy.

The displays indicate the **current energy level** of the spacecraft, which fluctuates over time. Energy gradually decreases due to propulsion consumption and when a probe is launched. However, it increases when a probe successfully mines a resource-rich asteroid and transfers the extracted energy to the spacecraft.

Each game state (**initial, playing, paused, or game over**) should have a different background scenario, video, or overlay text to provide a visual indication of the game's progress. The following illustration represents a possible start screen where the user must press the **C key** to begin the game. Alternatively, a video may be played with text overlays using a transparent foreground layer.

This project serves as a practical exercise in low-level programming and hardware interaction, providing an engaging way to apply Computer Architecture concepts.
