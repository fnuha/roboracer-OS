# Embedded Program for RoboRacer
Roboracer OS is the operating system built for the Roboracer physical product. It uses [FreeRTOS](https://www.freertos.org/) to schedule the various tasks of the robot and allows for the sensor and steering to happen in real time with only one processing core on the STM32 Nucleo microcontroller.

Currently, project does not have tasks implemented, but does have a version of [FreeRTOS](https://www.freertos.org/) implemented that will work with the STM32 Nucleo microcontroller.

## Setup Instructions
Initialize in empty folder, and use the STM32CubeIDE software to build the project.

## Deployment Procedures
Connect the STM32 Nucleo board to the device running the IDE, and load build onto board.
