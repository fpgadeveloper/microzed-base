microzed-base
=============

Base project for the MicroZed

### Description

This project is a base system for the MicroZed. The design contains only
the Zynq PS and is designed for and tested on the MicroZed.

### Requirements

* Vivado 2015.4
* [MicroZed 7Z010](http://microzed.org "MicroZed 7Z010")

### Installation of MicroZed board definition files

To use this project, you must first install the board definition files
for the MicroZed into your Vivado installation.

The following folders contain the board definition files and can be found in this project repository at this location:

https://github.com/fpgadeveloper/microzed-base/tree/master/Vivado/boards/board_files

* `microzed_7010`
* `microzed_7020`

Copy those folders and their contents into the `C:\Xilinx\Vivado\2015.4\data\boards\board_files` folder (this may
be different on your machine, depending on your Vivado installation directory).

### License

Feel free to modify the code for your specific application.

### Fork and share

If you port this project to another hardware platform, please send me the
code or push it onto GitHub and send me the link so I can post it on my
website. The more people that benefit, the better.

### About the author

I'm an FPGA consultant and I provide FPGA design services and training to
innovative companies around the world. I believe in sharing knowledge and
I regularly contribute to the open source community.

Jeff Johnson
http://www.fpgadeveloper.com