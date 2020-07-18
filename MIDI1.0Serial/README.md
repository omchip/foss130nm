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


https://github.com/ZipCPU/wbuart32   (note that this is GPLv3 licensed with payment required to change it)

Please note that the Lattice Wishbone example implementation requires that you only use what you learn from their code on Lattice devices.


