microzed-base
=============

Base project for the MicroZed

### Description

This project is a base system for the MicroZed. The design contains only
the Zynq PS and is designed for and tested on the MicroZed.

A tutorial for recreating this project in the Vivado GUI can be found here:

http://www.fpgadeveloper.com/2014/07/creating-a-base-system-for-the-zynq-in-vivado.html

### Requirements

* Vivado 2016.3
* [MicroZed 7Z010](http://microzed.org "MicroZed 7Z010")

### Installation of MicroZed board definition files

To use this project, you must first install the board definition files
for the MicroZed into your Vivado installation.

The following folders contain the board definition files and can be found in this project repository at this location:

https://github.com/fpgadeveloper/microzed-base/tree/master/Vivado/boards/board_files

* `microzed_7010`
* `microzed_7020`

Copy those folders and their contents into the `C:\Xilinx\Vivado\2016.3\data\boards\board_files` folder (this may
be different on your machine, depending on your Vivado installation directory).

### License

Feel free to modify the code for your specific application.

### Fork and share

If you port this project to another hardware platform, please send me the
code or push it onto GitHub and send me the link so I can post it on my
website. The more people that benefit, the better.

### About us

This project was developed by [Opsero Inc.](http://opsero.com "Opsero Inc."),
a tight-knit team of FPGA experts delivering FPGA products and design services to start-ups and tech companies. 
Follow our blog, [FPGA Developer](http://www.fpgadeveloper.com "FPGA Developer"), for news, tutorials and
updates on the awesome projects we work on.