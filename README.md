# Mojo-Full-Adder-Tester

## Setup

### output

* P15 -> b
* P16 -> a
* P17 -> ci

### input

* P111 <- co
* P112 <- sum

## Test

### Auto mode

set io_dip[0][0] to high

power up or press reset button

wait for result shown on display, which can be either "PASS" or "FAIL"

### Manual mode

set io_dip[0][0] to low

power up or press reset button

use io_dip[2][2:0] to control a, b, ci

press center button on IO shield to check result

then can set another test case by changing io_dip[2][2:0]

when done, press up button to show result
