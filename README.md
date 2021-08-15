# esphome-garage
Custom Board can be found: [Garage Door Sensor](https://easyeda.com/sjhilt/ha_sensor_copy)

Feel free to edit as you see fit or the Gerber files are located in the `board` directoy of this project 


![](https://github.com/sjhilt/esphome-garage/blob/main/garage_door.png)

# Make Your Own
You can do the same thing on a breadboard, or a permaproto board. 

Here is the BOM: 
TMP36: [Adafruit](https://www.adafruit.com/product/165)|[Amazon](https://www.amazon.com/KOOKYE-Temperature-TMP36-Precision-Raspberry/dp/B01GH32AQU/)

Relay Shield: [Amazon](https://www.amazon.com/HiLetgo-Relay-Shield-Module-WeMos/dp/B01NACU547/)

Reed Switch: [Adafruit](https://www.adafruit.com/product/375)|[Amazon](https://www.amazon.com/gp/product/B0154PTDFI/)


# Layout Of Board
![](https://github.com/sjhilt/esphome-garage/blob/main/garage_door_layout.png)


*** NOTE ***
The IR beam works for mine, but may not work with yours as this can sometimes be over 5v you will need to check this, if you want you can use a IR Break sensor but will need to change the board design a bit yourself or I can help if needed, in most cases this isn't needed but I added it just to play with it 
