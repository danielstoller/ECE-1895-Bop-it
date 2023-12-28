# ECE 1895: Box It - The Boxing-Themed Twist on Bop It

## Objective

In our Junior Design class, my two teammates and I were tasked with creating a unique variation of the classic game Bop-It. The challenge included designing a game with three distinct actions, integrating both functional and hardware requirements. Box It offers a unique and physically engaging experience, turning a traditional punching bag into an interactive gaming device. Its combination of responsive sensors, intuitive actions, and immediate feedback makes it an exciting addition to both gaming and fitness routines. The primary objectives were to provide an engaging user experience, encourage physical activity, and incorporate responsive and intuitive decision making to help boxers sharpen their reaction time.

<br>

## Box It - The Implementation

Our twist on Bop It is called "Box It," a boxing-themed version of Bop It that is designed to be attached to a punching bag. The 13.5" x 8.5" laser printed enclosure houses various components including sensors, speakers, a display, a power source, and a PCB to connect them all together.

- **Actions:**
  1. **Punch It:**
     - Padded punching area with a limit switch detects hard punches.
  2. **Kick It:**
     - IR sensor on the side that detects kicks to the punching bag.
  3. **Dodge It:**
     - Proximity sensor in the center checks if the user successfully dodged.

- **Enclosure Features:**
  - LED matrix display with animations for visual cues.
  - Two speakers for audible commands.
  - Proximity sensor for responsive precise detection.
  - IR sensor for radial, inclusive detection
  - Limit switch for registering powerful punches.

- **Scoring and Feedback:**
  - Successful actions earn points, challenging users with decreasing time intervals.
  - Visual cues indicate success or failure, and the game ends after 99 successful attempts.


## Youtube Demonstration:
[![Watch the Video](https://img.youtube.com/vi/TcJYKmGF-bU/maxresdefault.jpg)](https://youtu.be/TcJYKmGF-bU)

<br>


## Design Requirements

### Functional / Software Requirements

- **Power and Activation:**
  - The user can power the device on or off.
  - Upon activation, a button starts the game.

- **Game Commands:**
  - The device emits distinct, audible sounds specifying one of three commands.
  - The user must respond to the command with the corresponding action.

- **Scoring and Difficulty:**
  - Successful responses earn the user points.
  - After each successful attempt, the device issues a new command with a reduced time interval.
  - The game ends after 99 successful attempts, and the user is notified of their score.

- **Visual Cues:**
  - Visual cues indicate success or failure, providing immediate feedback to the user.

### Hardware Requirements

- **Power Source:**
  - The device is portable and battery-powered.

- **Enclosure:**
  - The device is enclosed with only inputs and outputs visible.
  - Compact and portable design for ease of use.

- **User Inputs:**
  - User-controlled inputs for powering the device and starting a new game.
  - Three tactile/sensory inputs for user responses.

- **Device Outputs:**
  - Three audible outputs for command specification.
  - Visual confirmation for successful and unsuccessful attempts.
  - Score notification at the end of each round.
 
<br>

## Responsibilities
- **Myself:**
    - Enclosure design, modeling, printing and assembly
    - LED Matrix animations
- **Tyler:**
    - PCB design and assembly
    - Component integration
- **Keegan:**
    - Game design and software
