A full sized version of the BKM-129X compatible board, modified by jam

Rev. 1.0

BKM-129X-MCU code from https://github.com/skumlos/bkm-129x-mcu

Output ports are all actively buffered, so no need for terminators.

Connections from top to bottom when viewing component side, with BNCs to the left:
               _______________________________________
            __| _                                     |
Y/G IN     |___|_|                                    |
            __| _                                     |
Y/G OUT    |___|_|                                   _|
            __| _                                   | |
B-Y/B IN   |___|_|                                  | |
            __| _                                   | |
B-Y/B OUT  |___|_|                                  | |
            __| _                                   | |
R-Y/R IN   |___|_|                                  | |
            __| _                                   | |
R-Y/R OUT  |___|_|                                  | |
            __| _                                   |_|
SYNC IN    |___|_|                                    |
            __| _                                     |
SYNC OUT   |___|_|                                    |
              |_______________________________________|

Just like the original BKM-129X.

For more information go to https://immerhax.com/?p=422

You are welcome to clone, produce and sell hardware based on this. Please keep changes and so on open source.

Cool kids give credit where due.

Should be compatible with basically all monitors that accept the original BKM-129X

Check the MCU code for verified compatibility.

---------

Board revision history:

Jam's fork 1.0 

C: Fixed THS7374 filter bypass.

B: Added onboard MCU option

A: Initial version

---------

Copyright © 2020 Martin Hejnfelt <martin@hejnfelt.com> and 2021 James van der Loeff <jam@wakabavideo.com>
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the LICENSE file for more details.

