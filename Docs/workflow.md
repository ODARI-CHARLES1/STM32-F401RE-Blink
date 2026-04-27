# Development Workflow

## Step 1: Environment Setup

PlatformIO was selected for its integration with VS Code and multi-platform support.

## Step 2: Project Initialization

A new project was created targeting the STM32 Nucleo-F401RE board using the STM32Cube framework.

## Step 3: Code Development

* GPIO peripheral initialized
* HAL library used for abstraction
* LED toggling implemented

## Step 4: Build Process

PlatformIO handles compilation using arm-none-eabi-gcc.

## Step 5: Upload Process

Firmware uploaded using ST-LINK debugger.

## Step 6: Testing & Verification

* LED blinking confirmed successful execution
* Timing verified using delay intervals

## Step 7: Iteration

Code modified and re-uploaded to test behavior changes.

## Step 8: Version Control

* Git used for tracking changes
* Commits structured by feature (setup, blink, fixes)
