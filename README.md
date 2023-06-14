# lumpen

lumpen is an entry-level 40% keyboard designed around the [rp2040-zero](https://www.waveshare.com/rp2040-zero.htm) micro controller from waveshare.
This is a plateless build with a pcb with flex cuts for some bounce and a simple backplate.
The keyboard sports a uniform stagger layout with big bar or split bar options for the bottom row. 
It also supports one rortary encoder at the bottom left and has a rgb breakout (see RGB for details!).

The design takes cues and inspiration from amazing keyboards such as trash man\#6005’s [Coriander](https://trashman.wiki/cases/coriander), rain\#3950's [hubris](https://github.com/rainkeebs/hubris-mv-case) and matthewdias' [model-v](https://github.com/matthewdias/model-v).

## Layout

![](https://github.com/calvin-mcd/lumpen/blob/main/Images/layout.png)

[Link](http://www.keyboard-layout-editor.com/#/gists/c5cd2165b0487d952150a8d600422438)

## Build Guide

*Step 1*

When building the keyboard make sure that you solder the switch on top of the micro controller before installing the controller! First solder the controller headers in place, make sure to cut them as flush as possible. Then solder the switch. Afterwards solder the controller.

Version 1.0 had some small interferences between that switch and the pins of the controller. Effort has been made to minimise that with version 1.1 but it has not been tested. In case of interference I recommend to cut part of the bottom housing of the switch. That worked well on version 1.0. (see pictures below)

*Step 2*

Solder the diodes of your choice. The pcb supports both through hole and smd diodes. Install stabilisers and solder the switches.

*Step 3*

Put standoffs on the pcb. Screw backplate onto the board.

The board uses m2 screwholes and works well with 10mm standoffs. For a smoother experience I recommend using a o-ring each between standoff and pcb (see pictures below).

*RGB*

Because this board uses a rp2040, you will need to use a logic shifter to utilise the rgb breakout. Something like [this](https://learn.sparkfun.com/tutorials/retired---using-the-logic-level-converter) or [this](https://learn.sparkfun.com/tutorials/bi-directional-logic-level-converter-hookup-guide) for example. Or you could try this [hack](https://hackaday.com/2017/01/20/cheating-at-5v-ws2812-control-to-use-a-3-3v-data-line/).

There are two firmwares are provided. I recommend the firmware that is using the onboard single led of the rp2040-zero. The second firmware is supposed to support the rgb strip with the above mentioned caveat.

## Pictures

![](https://github.com/calvin-mcd/lumpen/blob/main/Images/20230210_111705.jpg)
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/20230210_113822.jpg)
Soyo#3925's build:
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/soyo_lumpen.jpg)

Gerber Renders
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/pcb%20top.png)  
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/pcb%20bottom.png)  
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/backplate.png)


Picture of the switch sitting on top of the controler
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/20230210_111727.jpg)
Picture of the oring between standoffs and pcb
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/20230210_111737.jpg)


## Disclaimer

This PCB has been fully tested and is confirmed to work. However, no-one involved in this project is responsible for any usage issues that may arise. Order at your own risk. Feel free to edit, modify and otherwise utilise these files.

## License

This project is released under the GPL v3 License. Please refer to the LICENCE file.

## Credits

As always big thanks to the many people who helped me and inspired this board!

Any questions, contact Calvin\#0563 on Discord. 

