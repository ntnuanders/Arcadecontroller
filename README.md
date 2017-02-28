# Arcadecontroller
Config files for the arcade controller

| Teensy 3.1  | Teensy Variable Name | Keyboard Button   | Terminal Blocks  | Button Arcade |
| ----------- |:--------------------:| :----------------:|:----------------:|--------------:|
| GND         |                      |                   | 1                |               |
| 0           | L_K_Q            |                   |
| 1           |                  |             |
| 2           |                  |             |
| 3           |                  |             |
| 4           |                  |             |
| 5           |                  |             |
| 6           |                  |             |
| 7           |                  |             |
| 8           |                  |             |
| 9           |                  |             |
| 10          |                  |             |
| 11          |                  |             |
| 12          |                  |             |
| 13          |                  |             |
| 14          |                  |             |
| 15          |                  |             |
| 16          |                  |             |
| 17          |                  |             |
| 18          |                  |             |
| 19          |                  |             |
| 20          |                  |             |
| 21          |                  |             |
| 22          |                  |             |
| 23          |                  |             |
| 3.3V        |                  |             |
| AGND        |                  |             |
| Vin         |                  |             |

Bounce  = Bounce(0, 10);  //  B
Bounce P1_K_W = Bounce(1, 10);  //  Y      10 = 10 ms debounce time
Bounce P1_K_E = Bounce(2, 10);  //  Select which is appropriate for
Bounce P1_K_R = Bounce(3, 10);  //  Start  most mechanical pushbuttons
Bounce P1_K_T = Bounce(4, 10);  //  Up
Bounce P1_K_Y = Bounce(5, 10);  //  Down   if a button is too "sensitive"
Bounce P1_K_U = Bounce(6, 10);  //  Left   to rapid touch, you can
Bounce P1_K_I = Bounce(7, 10);  //  Right  increase this time.
Bounce P1_K_O = Bounce(8, 10);  //  A
Bounce P1_K_P = Bounce(9, 10);  //  X
Bounce P1_K_A = Bounce(10, 10); //  L
Bounce P1_K_S = Bounce(11, 10); //  R

//Player 2
//Bounce P2_K_D = Bounce(12, 10);  //  B
//Bounce P2_K_F = Bounce(13, 10);  //  Y
//Bounce P2_K_G = Bounce(14, 10);  //  Select
//Bounce P2_K_H = Bounce(15, 10);  //  Start
//Bounce P2_K_J = Bounce(16, 10);  //  Up
//Bounce P2_K_K = Bounce(17, 10);  //  Down
//Bounce P2_K_L = Bounce(18, 10);  //  Left
//Bounce P2_K_Z = Bounce(19, 10);  //  Right
//Bounce P2_K_X = Bounce(20, 10);  //  A
//Bounce P2_K_C = Bounce(21, 10);  //  X
//Bounce P2_K_V = Bounce(22, 10);  //  L
//Bounce P2_K_B = Bounce(23, 10);  //  R
L_Red

Examples from another github

    U   I   O
      \ | /
       \|/ 
    J --+-- K      Left controller disc
       /|\
      / | \
    N   M   , 

    W   E   R
      \ | /
       \|/ 
    S --+-- D      Right controller disc
       /|\
      / | \
    Z   X   C
