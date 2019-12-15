# Game Test

## Description

This project is a simple sandbox to play with assembly and create a game which could run on a GB emulator.
### Properties
    - Only Gameboy Compatible
    - ROM of 32k
    - No RAM


## Dependencies

* For this project, you will need rgbds v0.3.9 and you could find it [here](https://github.com/rednex/rgbds).
    > I'm not planning to put it in my project because I want a scalable project.
* To be able to lauch a `make test` command, you will need the [bgb emulator](http://bgb.bircd.org)

## Compilation

```sh
# Compile all dependencies. Create a map and a symbol object. 
$ make all

# Compile all dependencies with only needed file to play
$ make build

# Clean object files
$ make clean

# Clean object files and the binary file 
$ make fclean

# make fclean & make all
$ make re

# Test the compiled binary with bgb
$ make test
```