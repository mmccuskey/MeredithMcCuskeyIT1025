# Executive Summary
The purpose of Lab 2 is to identify hardware components within an information system. The second chapter in the textbook goes over hard drives, memory, SSD, RAM, the ALU, and the CPU. Logic gates are explained in some detail and it introduces different base systems such as binary and hexadecimal. It shows how to read these logic gates and do conversions from one base system to another.

# Hardware
## Hard Drives and Memory
* Latency is the amount of time it takes a hard drive to rotate the desired sector into position under the read-write head. It is calculated to be half a rotation. Disks that rotate faster deliver higher mechanical latency. There are two types of trasfer rates: the disk transfer rate and the data transfer rate. The disk transfer rate is the speed at which data is transferred to and from the disk media. The data transfer rate is the speed at which the host computer can transfer data across the IDE/EIDE or SCSI interface to the CPU.

* A solid state drive (SSD) hard drive is different from a traditional hard drive because it lacks a physical read head which means data can be stored anywhere without penalty. SSDs are therefore, much faster than a traditional hard drive. In a SSD there are no moving parts. Data is split up into word length pieces and stored in memory. The information can be accessed immediately; there is no latencies issues while transferring data.

* Increasing RAM makes the computer run faster because more data can be loaded into the faster RAM without the need of accessing the slower hard drive. The data is then transferred directly to the CPU. 

* 64 and 32 bit are used to describe processor architecture. A 32 bit processor contains a 32 bit register and can store 2^32 values while a 64 bit processor contains a 64 bit register and can store 2^64 values. The CPU register stores memory addresses which is how the processor accesses data from RAM. 32 bit programs can run on a 64 bit system but 64 bit programs will not run on a 32 bit system.


## ALU and Control Unit
* The arithmitic logic unit (ALU) is under the command of the control unit within the CPU. The control unit recieves an instruction from RAM and then tells the ALU what type of operation it should perform. The ALU performs all the mathematical operations.

## CPU, Input and Output
* The CPU interacts with input and output devices. Input devices would be keyboards, scanners, microphones, and digital cameras. The CPU recieves data that the input device converts to binary. The binary code tells the CPU what to display and then the CPU communicates with memory to store the results. The results are sent in binary code to the output device such as the screen, printer, or speaker.

## Logic Gates and circuits
* A truth table is a table that contains the inputs and outputs for a specific type of gate. The inputs and outputs are represented using boolean logic which means in 1s and 0s, or true and false. A NAND (a negated AND gate) is a digital logic gate with two or more inputs and one output. The output is true if one or more inputs are false. If both inputs are true, then the output is false.

* The behavior of a NAND gate is the opposite of the behavior of an AND gate. The truth gates are opposite in comparison. The output of an AND gate is only true if all of the inputs are true. If one or more of the inputs are false then the output is false.

## IEEE - Ethically Aligned Design
* The IEEE stands for Institute of Electrical and Electronics Engineers. It is the largest techincal professional society. Its purpose is to help professionals, whether they be a computer scientist, software developer, information technology specialist, in all areas of electronic, electrical, and computing fields and related areas of science and technology. Their efforts apply to the innovation of technology for the betterment of humanity. They also emphasize the importance of ethics in device design. Ethics in device design is important because they act as guidelines for behaviors, standards, and policies. Transparency, data agency, and accountability all fall under the general principles of ethically aligned design.

# Data Representation

## Numeric Conversions
* The difference between decimal, binary and hexadecimal numbers is that they all have different base systems. We, humans, usually use the decimal system which is base 10. This means we have a 1s place, 10s place, 100s place, etc. Binary and hexadecimal are used for computers but we can also comprehend them. Binary only has two numbers: 1 and 0. It is a base 2 system. It is used to represent information given in a byte (8 bits) of information. Hexadecimal is a base 16 system and is used commonly for formatting colors in HTML. After the hexadecimal system reaches 9, it uses letters to represent the amount.

* See DecimalConversion and BinaryConversion

## Hexadecimal color representation
* #ab00ff is a hexadecimal color that is displayed as purple. Hexadecimal colors are specified with RGB (Red, Green, Blue) values. The "#" is a symbol for hex and the first two digits (ab) are for determining the percentage of red that it will show within the color. The third and fourth digits (00) are for determining the percentage of green in the color which in this case is none. The last two digits (ff) are for determining the percentage of blue in the color. Since hexadecimal values go from 00-ff, this color has 100% blue in it.

* I think the color #ab00ff could be considered problematic in web sites. It's a neon color which tends to be hard on the eyes. It is too bright to read and doesn't stand out well on light or dark backrounds. 

# Conclusion
Lab 2 brought me a better understanding of the hardware components that go into making up an information system. It was interesting to learn about how the different hardware communicate with each other. I found converting from binary to decimal and vice versa was relatively easy, although I had a bit of trouble comprehending coversions to and from hex. During the WebEx call I was able to wrap my ahead around the idea after being shown a few practice problems. I also thought the principles behind the ethics of device design was interesting to learn about.
