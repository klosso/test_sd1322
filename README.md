This is test for chines Oled display 3.12'' based on SD1322 chip
Jumper set to SPI 4 pin mode. (R8,R5- on)
Port of Arduino lib to stm7F103


Connection between blue pill and LVM_SSD1322U display

                STM32 pill                           LVM_SSD1322U

                  +-\/-+
                 0|    |29  B12                        +--\/-+
            GND  1|    |28  B13 (SCK) ----+         2  |     | 1 3.3V
            GND  2|    |27  B14 -------+  + ------- 4  |     | 3 
            3.3V 3|    |26  B15->DIN   |            6  |     | 5 (DIN) -> B15
                 4|    |25  A8 ----+   |            8  |     |
                 5|    |24         |   |            10 |     |
                 6|    |23         |   |            12 |     |
                 7|    |22         |   +----------- 14 |     |
                 8|    |21         +--------------- 16 |     |
                 9|    |20                             +-----+
                10|    |19  
                11|    |18  
                12|    |17  
                13|    |16  
                14|    |15  
                  +----+
