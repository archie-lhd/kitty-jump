# kitty-jump-mips-assembly
![build-passing](https://img.shields.io/badge/build-passing-brightgreen)
![licence-MIT](https://img.shields.io/badge/license-MIT-blue)
## Overview

This is a course project for CSCB58 at UTSC in 2020 Fall.

Kitty Jump is a game similar to the classic "Doodle Jump" game, implemented in MIPS assembly language.

 <img src=https://user-images.githubusercontent.com/77775845/105339910-37490680-5bab-11eb-88a6-6eca0f0b6789.gif width = "240" alt = "gif-demo">

## Configuration
The project is written and tested in [MARS 4.5](http://courses.missouristate.edu/kenvollmar/mars/) developed by *Pete Sanderson* and *Ken Vollmar* at Missouri State University. 

1. Open the code file in [MARS 4.5](http://courses.missouristate.edu/kenvollmar/mars/), and go to ***Tools - Bitmap Display***. Set the configuration as below:

        - Unit width in pixels: 8        		     
        - Unit height in pixels: 8
        - Display width in pixels: 256
        - Display height in pixels: 512
        - Base Address for Display: 0x10008000 ($gp)

2. Resize the window to fit the bitmap display. Click on ***Connect to MIPS***.

3. Then go to ***Tools - Keyboard and Display MMIO Simulater***. Again, click on ***Connect to MIPS***.

4. Simply click on <img src=https://user-images.githubusercontent.com/77775845/105328859-7e7cca80-5b9e-11eb-96de-de8f371a2de4.jpg width = "30" alt = "MARS-assemble-icon">
on the toolbar to assemble the program 
 and then click on <img src=https://user-images.githubusercontent.com/77775845/105328867-80468e00-5b9e-11eb-8a9c-3981acb516d4.jpg width = "30" alt = "MARS-run-icon">
to run it. 

5. **Congratulations! You are now all set! Enjoy the game!**

## Game Instructions
Control the Kitty by hitting <kbd>J</kbd> (move left) or <kbd>K</kbd> (move right) keys on your keyboard. 

Pause the game by hitting <kbd>P</kbd>. Hit <kbd>P</kbd> again to continue.

(Make sure you set the focus to the textbox in the ***Keyboard and Display MMIO Simulater*** window.)
