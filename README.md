# PLC-Based Traffic Light Automation System

A PLC-based traffic light automation project developed and tested using **LogixPro PLC Simulator** and **Ladder Logic programming**.

## Project Overview

This project automates a traffic signal sequence using PLC Ladder Logic. The system controls the **Red, Yellow, and Green** lights in a predefined sequence using timers and internal control bits.

## Features

* Red–Yellow–Green sequential traffic signal operation
* START/STOP control
* TON timer-based sequencing
* Latching and unlatching logic
* Internal control bits for sequence management
* Simulated PLC outputs
* Tested and verified using LogixPro PLC Simulator

## Software Used

* **LogixPro PLC Simulator**
* **PLC Ladder Logic**

## Main Components

* START input
* STOP input
* Red signal
* Yellow signal
* Green signal
* TON timers
* Internal control bits

## Working

1. The system is started using the **START** input.
2. The **Red light** remains ON for a predefined timer duration.
3. After the Red timer completes, the **Green light** is activated.
4. After the Green timer completes, the **Yellow light** is activated.
5. The sequence continues automatically using timer-based control.
6. The **STOP** input can be used to stop the sequence.

## Project File

The main Ladder Logic program is available in:

`Traffic_Light_Automation.lad`

## Author

**Manoj Kumar**
B.Tech Electronics Engineering
Rajkiya Engineering College, Sonbhadra

GitHub: https://github.com/mano449
