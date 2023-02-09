# lumpen

lumpen is an entry-level 40% keyboard designed around the rp2040-zero micro controller.
This is a plateless build with a pcb with flex cuts for some bounce and a simple backplate.
The keyboard sports a uniform stagger layout with big bar or split bar options for the bottom row. 
It also supports one rortary encoder and has a rgb breakout.

The design takes cues and inspiration from amazing keyboards such as trash man\#6005’s [Coriander](https://trashman.wiki/cases/coriander), rain\#3950's [hubris](https://github.com/rainkeebs/hubris-mv-case) and matthewdias' [model-v](https://github.com/matthewdias/model-v).

## Layout

![](https://github.com/calvin-mcd/lumpen/blob/main/Images/layout.png)

[Link](http://www.keyboard-layout-editor.com/#/gists/c5cd2165b0487d952150a8d600422438)

## Build Guide

When building the keyboard make sure that you solder the switch on top of the micro controller before installing the controller! Version 1.0 had some small interferences between that switch and the pins of the controller. Effort has been made to minimise that with version 1.1 but it has not been tested. In case of interference I recommend to cut part of the bottom housing of the switch. That worked well on version 1.0.

The board uses m2 screwholes and works well with 10mm standoffs. For a smoother experience I recommend using a o-ring each between standoff and pcb.

The pcb supports both through hole and smd diodes.

Because this board uses a rp2040 some rgb strips might not work due to their 5V logic. I had mixed results so far. However two firmwares are provided. One allows you to use only the one led on the micro controller itself for RGB instead of rgb breakout.

## Pictures

![](https://github.com/calvin-mcd/lumpen/blob/main/Images/pcb%20top.png)  
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/pcb%20bottom.png)  
![](https://github.com/calvin-mcd/lumpen/blob/main/Images/backplate.png)  

## Disclaimer

Please note that this project has been tested to work but I am _not responsible_ for any outcomes of its use. However, feel free to edit, modify and otherwise utilise these files.

## License

This project is released under the GPL v3 License. Please refer to the LICENCE file.

## Credits

As always big thanks to the many people who helped me and inspired this board!

Any questions, contact Calvin\#0563 on Discord. 

