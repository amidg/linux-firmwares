## What is this?
My personal collection of self-developed drivers written in pure C designed for the hardware communication with other devices.

## Why is this repo good?
I want to make drivers that are highly abstracted enough to be portable across not just microcontroller architectures but whole embedded systems in general.\
For example, I want MPU6050 IMU driver to be equally portable between an ESP32 and Nvidia Jetson or Raspberry Pi without major changes in the codebase.

## How does it work?
You can provide compilation flags to the make in order to build drivers for specific type of device. There are two ways of doing it:
1. Use root directory CMakeLists.txt to build entire project with all drivers in according to your platform.
2. Use specific folder's CMakeLists.txt to bulid specific driver you need
