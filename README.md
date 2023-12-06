# CHIP-8 Emulator in Rust

This project implements a CHIP-8 emulator in Rust, allowing you to run CHIP-8 programs on your machine. Below is a brief guide on how to use and understand the emulator.

## Getting Started
### Dependencies

Ensure you have Rust installed on your machine.

Add the necessary dependencies by including them in your Cargo.toml file:

```
[dependencies]
sdl2 = "0.34"
rand = "0.8"
```

### Building and Running

Clone this repository and navigate to the project folder.

### Run the emulator using:

```
cargo run path_to_ROM
```
> Replace path_to_ROM with the actual path to the CHIP-8 ROM you want to run.

## Controls

###  Keyboard Mapping

The CHIP-8 keypad is mapped to the modern keyboard as follows:

````
1 2 3 C
4 5 6 D
7 8 9 E
A 0 B F
``````

### How It Works
The emulator uses the SDL2 library for window management and input handling.
CHIP-8 programs are loaded from ROM files, and the emulator executes them.

### Customization
You can adjust the emulator's window size and scale by modifying the SCALE, WINDOW_WIDTH, and WINDOW_HEIGHT constants.
The TICKS_PER_FRAME constant controls the speed of the emulation.
Exiting the Emulator
Press ESC or close the emulator window to exit.


### Contributing
Feel free to contribute to this project by opening issues or submitting pull requests.


### Acknowledgments
The emulator relies on the CHIP-8 Rust library for its core functionality.
Enjoy running your favorite CHIP-8 games on this emulator!