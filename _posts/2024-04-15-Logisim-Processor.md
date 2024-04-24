---
layout: post
title: Logisim Processor
---

## Description

This is an implementation of a CPU on Logisim Evolution. This project demonstrates how a CPU worksAll components are expressed using basic logic gates and wires, though some components have been swapped with built-in Logisim components to improve performance.

# Instructions

This looks imposing but it's actually pretty quick and straightforward

1. Write some assembly code using the provided instruction set
2. (Optional) Test it using the NiosII simulator. Please note that this simulator uses a slightly different instruction set (notably the *branch greater or equal to* is replaced by *branch greater than*)
3. Use the provided compiler to compile your assembly code to hexadecimal code that the processor can understand (or you could do it manually but that is not at all recommended)
4. Open the Logisim project, and using the hand pan tool, double click on the "system" component in the middle of the simulated Gecko board. Then double click on the ROM component
5. Finally follow the instruction to add your hexadecimal code to the ROM
