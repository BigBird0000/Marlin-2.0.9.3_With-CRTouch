ReadMe.MD

This contains the source of Marlin 2.0.93
(also included are the example configurations)

The marlin folder contains the configuration files
I used to set up the firmware for my Ender 3 Pro
with V4.2.2 board, and the non-silent

You must adjust the nozzle offsetr
configuration.h, line 1145
#define NOZZLE_TO_PROBE_OFFSET {-44, -2, -1.2} 
Read the comments above this line.

I also disabled the startup screens.

I recommend reading through configuration.h and configuration_adv.h
so you have a good idea of other changes you may want to make, and
learn a little bit about the Marlin firmware.

Click the build button on ABM
 Environment:
  STM32F103RET6_creality
  NOT STM32F103RET6_creality_maple