# bcdcounter
BCD Counter (Binary-Coded Decimal Counter)
This repository contains the Verilog implementation of a BCD Counter, a digital circuit that counts in Binary-Coded Decimal (BCD) format. A BCD counter increments its count from 0000 (0 in decimal) to 1001 (9 in decimal) and then resets to 0000.
Overview
A BCD Counter is a digital circuit used to count decimal digits in binary form. Each digit is represented using 4 bits, and the counter operates cyclically within the range of 0 to 9. When the counter reaches 9, it resets back to 0. This type of counter is widely used in digital displays, clocks, and calculators.
Features
Counts from 0000 (0) to 1001 (9) in BCD format.
Resets automatically to 0000 after reaching 1001.
Synchronous operation with a clock signal.
Easy to integrate into larger digital systems.
