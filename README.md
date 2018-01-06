# stm32_oled
interfacing 128*64 oled with stm32(blue pill)


# Instructions
First of all install the arduino ide latest version.
Install the necessary st-link driver from st link website http://www.st.com/en/development-tools/st-link-v2.html .
Now install the arduino SAM board(32bit arm cortex-M3) from arduino board manager.(**this step is important**).
Now clone the following stm32 library from  rogerclarkmelbourne's git https://github.com/rogerclarkmelbourne/Arduino_STM32 .
Then unzip the above mentioned library and rename as 'stm32' and save it inside C:\Program Files (x86)\Arduino\hardware .
Finally restart the arduino ide and and upload the file "ssd1306_128x64_i2c.cpp" to stm32 board via st-link/ftdi.
DONE!!!
