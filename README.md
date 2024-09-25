# Hex FCU
5 OLED's are used for the FCU, and two OLED's are used for left and right EFIS.
The FW is setup for 1.3" OLED's with 128x64 pixel using the SH1106 chipset.


## Installation
Download the ZIP file from the Releases and extract it into the community folder within your Mobiflight folder.
It should look like this:

![alt_text](https://github.com/philipposslicher/mf-fcu/blob/main/documents/folder_structure.png)

Connect your Mega or Pico board and start Mobiflight. Flash the firmware and add one custom device. Set the I2C adress to 0x70/0x71 or to the adress you have choosen on the portexpander.
Even I2C addresses support OLED's with SH1106G driver, odd I2C addresses support OLED's with SSD1306 driver.

## Wiring
![alt_text](https://github.com/philipposslicher/mf-fcu/blob/main/documents/FCU_EFIS.png)

