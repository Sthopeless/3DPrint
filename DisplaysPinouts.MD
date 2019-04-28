```
 *
 *             Anet     |     Anet     |    Anet    |    RepRap     |     SKR v1.3      |
 *             board    |      A8      |     A6     |     12864     |                   |
 *             pin      |    Display   |   Display  |               |                   |
 *------------------------------------------------------------------------------------------------------------------------
 *   EXP-1.P1   GND     | GND          | GND        | GND           | +5V               |
 *   EXP-1.P2   +5V     | +5V          | +5V        | +5V           | GND               |
 *   EXP-1.P3   27      | N/C *        | LCD_RS     | LCD_RS        | P1_23 (LCD_D7)    |
 *   EXP-1.P4   10      | LCD_D4       | BTN_EN2    | BTN_EN2       | P1_22 (LCD_D6)    |
 *   EXP-1.P5   28      | LCD_RS       | LCD_ENABLE | LCD_ENABLE    | P1_21 (LCD_D5)    |
 *   EXP-1.P6   11      | LCD_D5       | BTN_EN1    | BTN_EN1       | P1_20 (LCD_D4)    |
 *   EXP-1.P7   29      | LCD_ENABLE   | N/C *      | SDSS or N/C * | P1_19 (LCD_RS)    |
 *   EXP-1.P8   16      | LCD_D6       | BTN_ENC    | BTN_ENC       | P1_18 (LCD_EN)    |
 *   EXP-1.P9   30      | ADC_KEYPAD** | LCD_D4     | LCD_D4        | P0_28 (BTN_ENC)   |
 *   EXP-1.P10  17      | LCD_D7       | BEEPER     | BEEPER        | P1_30 (BEEPER)    |
 *                      |              |            |               |                   |
 *                      |              |            |               |                   |
 *   EXP-2.P1    8 ***  | N/A          | J3_TX ***  |               | N/C               |
 *   EXP-2.P2    9 ***  | N/A          | J3_RX ***  |               | GND               |
 *   EXP-2.P3    6      | N/A          | MISO ***   | MISO          | RESET             |
 *   EXP-2.P4    +5V    | N/A          | +5V        |               | P1_31 (SD_DETECT) |
 *   EXP-2.P5    7      | N/A          | SCK ***    | SCK           | P0_18 (MOSI)      |
 *   EXP-2.P6    5      | N/A          | MOSI ***   | MOSI          | P3_25 (BTN_EN2)   |
 *   EXP-2.P7    !RESET | N/A          | button     | panel button  | P0_16 (SDSS)      |
 *   EXP-2.P8    GND    | N/A          | GND        | 0GND          | P3_26 (BTN_EN1)   |
 *   EXP-2.P9    4      | N/A          | N/C        |               | P0_15 (SCK)       |
 *   EXP-2.P10   +3.3V  | N/A          | +3.3V ***  |               | P0_17 (MISO)      |
 
 
 
 *                 N/C * - if not connected to the LCD can be used for BLTouch servo input
 *                 ** - analog pin -WITHOUT a pullup
 *                 *** - only connected to something if the Bluetooth module is populated
 ```
