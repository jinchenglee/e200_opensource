Hummingbird E203 Opensource Processor Core
================

About
-----------

This repository is a branch from the Hummingbird E203 opensource repository, which hosts the project for open-source hummingbird E203 RISC processor Core.

The Hummingbird E203 core is a two-stages pipeline based ultra-low power/area implementation, makes the Hummingbird E203 as a perfect candidate for research and education of RISC-V implementation. 

Detailed Introduction
-----------------------------

We have provided very detailed introduction and quick start-up documents to help you ramping it up. 

The detailed introduction and the quick start documentation can be seen 
from https://github.com/SI-RISCV/e200_opensource/tree/master/doc directory.

FPGA-Board and JTAG-Debugger 
-----------------------------
In order to easy user to study RISC-V in a quick and easy way, we have made a dedicated FPGA-Board and JTAG-Debugger.  Diagram as below:

#### My set-up with Lichee Tang Board

* USB-Serial UART connection to RISC-V CPU
ID 1a86:7523 QinHeng Electronics HL-340 USB-Serial adapter

* JTAG connection to RISC-V CPU Core
ID 0403:6014 Future Technology Devices International, Ltd FT232H Single HS USB-UART/FIFO IC

* JTAG connection to LicheeTang FPGA Core (this is on the licheetang borad)
ID 0547:1002 Anchor Chips, Inc. Python2 WDM Encoder

Following the steps introduced in this blog (https://justanotherelectronicsblog.com/?p=470), I'm able to run bare-metal successfully on the little board. 
