# BlueRetro HW2 QSB for GameCube
![](./doc/BRHW2GC.jpg)

## Introdution

This is an internal QSB (Quick Solder Board) for the GameCube Cotroller Port PCB that adds BlueRetro with most of the HW2 Feature set. It is based on [Darthclouds BlueRetro](https://github.com/darthcloud/BlueRetro) and on [ManClouds Current Mirror](https://github.com/ManCloud/CurrentTrigger).

## Features

- **Internal QSB**
This PCB is soldered to the GameCube controller port PCB directly, without the need for any wires.

- **Port Detection**
  Detects if a controller is physically connected to a controller port and disabled BlueRetro for that port. Port detection can be accomplished by 2 different methods.
  - **Current Trigger**
    Current Trigger detection requires more components to be installed but does not require as many traces to be cut on the original GameCube controller port PCB

  - **Port Shield**
    Port Shield detection requires less components, but requres many traces to be cut on the GameCube controller port PCB.

- **Reset Control**
    You can reset the console with the controller and you can change the state of the ESP with the reset button, eg. Pairing mode or resetting the ESP config.
- **Global Status LED**
  There is a status LED on the board that can indicate the state of the BlueRetro board. This LED is visible through the GameCube's power led light pipe.

  ## Usage
Please refer to the [BlueRetro Documentation](https://github.com/darthcloud/BlueRetro/wiki) for usage instructions.

## Building the PCB

- **Current Trigger Version**
  For the Current Trigger version use the [Current Trigger BOM](https://github.com/Arthrimus/BlueRetro-HW2-GameCube/blob/main/PCB/GC%20BlueRetro%20BOM%20(Current%20Trigger).xlsx). 
- **Port Shield Version**
