# Rent Calculator
## Description
This is a short Python script used to evenly divide the rent for Apt 308 at Kelton 520. This isn't so much as a big project as it is a small practical tool.

## File Purposes
### rent.py
Main file which holds the logic for this project. The flags can be found by running the followiung command:
> python3 rent.py -h

### default_values.py
Contains the default values for the rent script. This module is imported by `rent.py`. If the user wishes to change the default values, edit this file by inputting the desired values.

### run.sh
A script file which simply runs the `rent.py` script with default values.

## Usage
To run the `rent.py` script without the default values listed above, use a flag followed by its values to change them. Below is an example call.
> python3 rent.py -b 0.65 -s 0.35 -bn 3 -sn 2 -p 220 -r 3509.50

Any flags that are left out will be replaced with the default values.

## Credits
Made by Ryan Miyahara (8/26/2019)

## TODO List (Given more time)
- Error checks