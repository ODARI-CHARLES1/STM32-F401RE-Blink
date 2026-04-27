# Setup Guide

## Installing PlatformIO

1. Install Visual Studio Code
2. Install PlatformIO extension

## Creating a Project

* Open PlatformIO Home
* Select "New Project"
* Board: nucleo_f401re
* Framework: STM32Cube

## Connecting Hardware

* Use ST-LINK USB port
* Verify detection using:
  pio device list

## Uploading Code

```
pio run --target upload
```
