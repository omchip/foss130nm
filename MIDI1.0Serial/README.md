Introduction
------------

The RISC-V based harness includes a wishbone bus

Requirements
------------
* A UART that serializes data in both directions on the bus
* A Baud rate generator for the standard MIDI clock rate (dividing down perhaps from the main RISC-V clock
* FIFO's
* Extra Credit
  Time stamped FIFO with hardware scheduling and tagging
  
Starting Points
---------------

Verilog:

https://github.com/ZipCPU/wbuart32   (note that this is GPLv3 licensed with payment required to change it)
also cataloged here: https://opencores.org/projects/wbuart32

https://opencores.org/projects/ftdi_wb_bridge

Please note that the Lattice Wishbone example implementation requires that you only use what you learn from their code on Lattice devices.

This one is LGPL and Beta https://opencores.org/projects/wishbone_uart_controller

https://papilio.cc/index.php?n=Papilio.ZPUinoUserGuide#UART

VHDL
https://www.ohwr.org/project/general-cores/tree/master/modules/wishbone/wb_uart

https://github.com/skordal/potato/blob/master/soc/pp_soc_uart.vhd
