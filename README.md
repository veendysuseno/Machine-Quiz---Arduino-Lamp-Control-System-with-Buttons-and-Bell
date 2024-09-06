<!-- Machine-Quiz -->

# Machine Quiz - Arduino Lamp Control System with Buttons and Bell

This project demonstrates a simple control system to manage three lamps using buttons and a bell. When a button is pressed, the corresponding lamp turns on and the bell rings. The lamp stays on until the button is released.

## Components Used

- Arduino Uno
- 3 LEDs (representing lamps)
- 3 Push buttons (connected to pins 5, 6, 7)
- Buzzer (connected to pin 8)
- Resistors
- Wires
- Breadboard

## How It Works

- Each of the three buttons controls a specific lamp.
- When a button is pressed, the associated lamp turns on, and the bell rings for 500ms.
- The lamp remains on while the button is pressed and turns off when the button is released.
- The buzzer sounds once each time a button is pressed.

## Pin Configuration

- **Lamps (LEDs)**:
  - Lamp A: Pin 2
  - Lamp B: Pin 3
  - Lamp C: Pin 4
- **Buttons**:
  - Button A: Pin 5
  - Button B: Pin 6
  - Button C: Pin 7
- **Buzzer (Bell)**: Pin 8

## Code Explanation

- The lamps are connected to pins 2, 3, and 4, and the buttons are connected to pins 5, 6, and 7.
- The buttons are configured with pull-up resistors, so they are normally HIGH and go LOW when pressed.
- When a button is pressed, the corresponding lamp turns on, and the buzzer sounds for 500ms.
- The lamp turns off when the button is released.

## How to Use

1. Connect all the components according to the pin configuration.
2. Upload the provided code to your Arduino board.
3. Press any button to turn on the corresponding lamp and sound the bell.
4. Release the button to turn off the lamp.

## Features

- Controls three lamps with individual buttons.
- Audible feedback via a bell when a button is pressed.
- Simple and intuitive button-based control system.

## License

This project is open-source and can be freely modified or shared.
