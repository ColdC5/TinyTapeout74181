<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a recreation of the 74181 4 Bit ALU from the 1970s. 
There are additional Registers for saving your inputs. 

data bus: 
IN0 = d0
IN1 = d1
IN2 = d2
IN3 = d3

control code:
IN4 = q0
IN5 = q1
IN6 = q2
   
## How to test

1. Start the simulation
2. Reset the circuit once (due to Register uncertainty in the beginning)
3. Select your operation (https://de.wikipedia.org/wiki/74181) (using control code 011)
4. Select your mode (using control code 001)
5. Load a (using control code 101)
6. Load b (using control code 110)
7. You should now see your output.

## External hardware

WIP
