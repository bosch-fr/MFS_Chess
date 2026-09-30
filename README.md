# MFS_Chess
Chess game for Arduino Multi Function Shield

<img width="473" height="600" alt="chess" src="https://github.com/user-attachments/assets/091eb949-01bd-4136-9fcf-be7b25bf2edd" />


Here is a nice chess game, based on H.G. Muller's Micro-Max chess engine (version 4.8),

adapted to the cheap (less than 2e) and widely available Arduino's Multi Function Shield.

What you need :
---------------

Arduino UNO (or MEGA)

Multi Function Shield (Aliexpress suggested)

This MFS_chess.uno file

The MultiFuncShield library

Any chess board to visualise the game

How to use :
------------

Download/install the library : https://github.com/hpsaturn/MultiFuncShield-Library

Upload the .ino file to your Arduino UNO.

Buttons functions :

S1 : SELECT

S2 : VALID

S3 : CLEAR

Playing chess :
---------------

7 segment display will show 'PLAY', press VALID

enter your move, using SELECT to change the letter from A to H

press VALID, second segment display will show up first digit

use SELECT to change digit from 1 to 8, then press VALID

do the same for 3d and 4th segment display.

You can always reset display with CLEAR button.

Then Arduino will show his own move after a few seconds.


Please report any malfunction, thanks !

![MFS_schematic](https://github.com/user-attachments/assets/aaeb7910-efd8-4aaa-8f59-2c6d82d054a4)
