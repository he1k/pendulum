# Project progression

## Software

### FPGA

#### Modules

* Completed:
  * Console interface (including UART and buffers)
  * Fixed point multiplier with error handling (-1 * -1)
  * PWM generator
  * 
* Missing:
  * Fixed point subtractor with saturation
  * Fixed point adder with saturation
  *  

### PC

* Completed:
  * Basic serial interface (both for UNIX and Windows)
  * Basic "Real Time" plotting interface
* Missing:
  * Main application

## Control

### Velocity Servo

* Need to research papers to find a good control architecture. 
  * Could be PI
    * Eliminates steady state error
    * Response might not be so fast
  * Could be PD
    * Steady state error present
    * Fast response to rapid changes in reference. Changes in reference correspond to acceleration
  * More TBA



## Hardware

