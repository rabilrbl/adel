# Digital Electronics Viva Notes

***Table of contents***
- [Digital Electronics Viva Notes](#digital-electronics-viva-notes)
  - [Half Adder](#half-adder)
  - [Half Subtractor](#half-subtractor)
  - [Full adder](#full-adder)
  - [Full Subtractor](#full-subtractor)
  - [Multiplexer](#multiplexer)
    - [Applications](#applications)
  - [Flip Flop](#flip-flop)
  - [Latch](#latch)
  - [Difference between Flip Flop and Latch](#difference-between-flip-flop-and-latch)
  - [SR Flip Flop](#sr-flip-flop)
  - [JK Flip Flop](#jk-flip-flop)
  - [Basic Gates](#basic-gates)
  - [Universal Gates](#universal-gates)
  - [Why the universal gates?](#why-the-universal-gates)
  - [Why is gray code better than binary code?](#why-is-gray-code-better-than-binary-code)
  - [Synchronous counter](#synchronous-counter)
    - [Applications](#applications-1)
  - [Asynchronous counter](#asynchronous-counter)
    - [Applications](#applications-2)
  - [Up and Down counter](#up-and-down-counter)

## Half Adder

A half adder is a type of adder and an electronic circuit that performs the addition of numbers. The half adder is able to add two single binary digits and provide the output plus a carry value. It has two inputs, called A and B, and two outputs S (sum) and C (carry)

## Half Subtractor

The half subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, the minuend and subtrahend and two outputs the difference and borrow out.

Half Subtractor is used for the purpose of subtracting two single bit numbers.

## Full adder

A full adder is a digital circuit that performs addition. Full adders are implemented with logic gates in hardware. A full adder adds three one-bit binary numbers i.e. two operands and a carry bit. The adder outputs two numbers, a sum and a carry bit.

## Full Subtractor

The full subtractor is a combinational circuit which is used to perform subtraction of three input bits: the minuend, subtrahend, and borrow in. The full subtractor generates two output bits: the difference and borrow out.


## Multiplexer

Multiplexer is a device that selects between several input signals and forwards the selected input to a single output line. The selection is directed by a separate set of digital inputs known as select lines.

### Applications

- Multiplexer allow the process of transmitting different type of data such as audio, video at the same time using a single transmission line. 
- Telephone Network – In telephone network, multiple audio signals are integrated on a single line for transmission with the help of multiplexers.

## Flip Flop

Flip-flop is a basic digital memory circuit, which stores one bit of information.

## Latch

Latch is an electronic device, which changes its output immediately based on the applied input. It is used to store either 1 or 0 at any specified time.

## Difference between Flip Flop and Latch

| Flip Flop | Latch |
| :---: | :---: |
|It is a edge triggered device.| It is a level triggered device.|
| Flip-flop always have a clock signal | latche doesn’t have a clock signal |
|Flip-flop can be build from Latches | Latches can be build from gates |
|ex: D Flip-flop, JK Flip-flop | ex: SR Latch, D Latch |

## SR Flip Flop

The SR flip flop is a 1-bit memory bistable device having two inputs, i.e. SET and RESET. The SR flip flop stands for "Set-Reset" flip flop. The reset input is used to get back the flip flop to its original state from the current state with an output 'Q'.

## JK Flip Flop

The JK flip flop is a universal flip flop having two inputs 'J' and 'K'. So, the JK flip-flop has four possible input combinations, i.e. 1, 0, "no change" and "toggle".

The JK Flip-flop is similar to the SR Flip-flop but there is no change in state when the J and K inputs are both LOW

## Basic Gates

- AND
- OR
- NOT



## Universal Gates

- NAND
- NOR

## Why the universal gates?

NAND and NOR gates are called universal gates because they can be combined to produce any of the other gates like OR, AND, and NOT gates.

## Why is gray code better than binary code?

Advantage of grey code over binary is only one bit changes for each step. This will be useful in circuits that are sensitive to glitches.

## Synchronous counter

Synchronous counter is the one in which all the flip flops are clocked simultaneously with the similar clock input

### Applications

- Controlling moving machine
- Clarms clocks
- Multiplexing circuits

## Asynchronous counter

Asynchronous counter is a device in which all the flip flops are clocked with different input signals at different instants of time.

### Applications

- Frequency dividers

## Up and Down counter

An up-down counter is a combination of an up-counter and a down-counter. It can count in both directions, increasing as well as decreasing.