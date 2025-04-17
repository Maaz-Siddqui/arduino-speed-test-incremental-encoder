# Arduino Rotary Encoder Speed Monitor

## Description
This project uses an **Arduino Due** and a **4-wire incremental rotary encoder** to:
- Measure rotational speed
- Track encoder position
- Display speed in steps per second
- Show a congratulatory message when speed is within a target range (25-50 steps/sec)

## Features
- Displays encoder position and speed
- Alerts with "Congrats!" when speed is between 25 and 50 steps/sec
- Simple and easy to use with the Arduino Due

## Hardware Required
- **Arduino Due**
- **4-wire rotary encoder**
- Jumper wires

## Setup

1. Open the `rotary_encoder_speed_monitor.ino` file in the **Arduino IDE**.
2. Connect the **rotary encoder** to your Arduino:
   - Pin A → Pin 2
   - Pin B → Pin 4
   - VCC → 3.3V
   - GND → GND
3. Connect your **Arduino Due** to your computer.
4. In the Arduino IDE, select **Tools > Board > Arduino Due**.
5. Click **Upload** to upload the code to the Arduino.

## Usage

1. Open the **Serial Monitor** (set baud rate to `115200`).
2. Rotate the encoder. The Serial Monitor will show:
   - **Encoder position**
   - **Speed** in steps per second
3. If the speed is between 25 and 50 steps/sec, you’ll see:
