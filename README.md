># Wiring diagram - [Pins](image/01_pin.png)
>![Untitled Sketch 3_bb](https://raw.githubusercontent.com/equlibrino/esp01_software/main/image/upload_esp01.png)

#This is really frustrating, I understand you very well, please calm down :)

### Materials;
- ESP8266 Wifi Serial Module
- Arduino Uno
- Jumper cable

### First step
- We need to make minor adjustments in the Arduino IDE program.
1. Open the IDE then [File](image/preferences.png) > [Preferences](image/preferences2.png)
2. Type "https://arduino.esp8266.com/stable/package_esp8266com_index.json" in the Additional Boards Manager URLs section.

### Second step
- Tools > Board > [Board Manager...](image/board_manager.png)
- Type [esp8266](image/esp8266.png) and download the resulting dashboard.
- Then select Tools > Motherboard > esp8266 > [Generic ESP8266 Module](image/generic.png) again.
## We're done with what we need to do in the IDE settings! You are such a good man.

### **Software installation phase**
<font color="red">There should be no software inside the Arduino Uno board. Do not install any empty software.</font>
1. Power up the Uno board.
2. Unplug the 3.3v cable of the Esp module. <font color="red">The card is now in software installation mode!</font>
3. Start loading your code.
4. Once installed, unplug the [GPIO-0](image/01_pin.png) pin.
5. Disconnect and reconnect the 3.3v cable of the Esp module.
- And that's it my friend!
