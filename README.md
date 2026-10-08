# Adaptive Space

Adaptive Space is a multimodal interaction interface developed as an HCI project. The main idea is to create an interface that responds to different forms of user input and changes its behavior according to the interaction taking place.

Instead of having separate controls for every interaction, the interface itself acts as the interactive space. Mouse clicks, pointer movement, keyboard input, typing, touch, voice commands, and gamepad input can all produce a visible response.

## Project Overview

The interface was designed to demonstrate adaptive behavior using commonly available web technologies.

Different interactions produce different responses. For example, clicking on the interface creates visual feedback, typing a color changes the interface color, voice commands can modify the interface, and touch input changes the interface into a more touch-friendly state.

The project is implemented as a single-page web application.

## Main Features

### Pointer Interaction

The interface tracks pointer movement across the screen. The interactive field responds to the pointer position and displays the current coordinates.

Clicking on the interface produces a ripple, flash, and particle effect to provide immediate visual feedback.

### Keyboard Interaction

Keyboard input is detected throughout the interface.

Number keys are also mapped to different colors:

| Key | Color |
|-----|-------|
| 1 | Red |
| 2 | Blue |
| 3 | Green |
| 4 | Purple |
| 5 | Orange |
| 6 | Pink |
| 7 | Yellow |
| 8 | Teal |

### Text Input

The interface includes a text input area where commands can be typed directly.

Color names are detected from the entered text and the interface changes accordingly.

Examples:

```text
make it red
change to blue
make it green
