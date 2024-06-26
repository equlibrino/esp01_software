># Wiring diagram - [Pins](image/01_pin.png)
>![Untitled Sketch 3_bb](image/upload_esp01.png)

# This is really frustrating, I understand you very well, please calm down :)

### Materials;
- ESP8266 Wifi Serial Module
- Arduino Uno
- Jumper cable

### First step;
- We need to make minor adjustments in the Arduino IDE program.
1. Open the IDE then [File](image/preferences.png) > [Preferences](image/preferences2.png)
2. Type "https://arduino.esp8266.com/stable/package_esp8266com_index.json" in the Additional Boards Manager URLs section.

### Second step;
- Tools > Board > [Board Manager...](image/board_manager.png)
- Type [esp8266](image/esp8266.png) and download the resulting dashboard.
- Then select Tools > Motherboard > esp8266 > [Generic ESP8266 Module](image/generic.png) again.
## We're done with what we need to do in the IDE settings! You are such a good man.

### **Software installation phase;**
**There should not be any software inside the Arduino Uno board.**
**You must upload a blank code to the card;**
- File > [New Sketch](image/new_sketch.png)
- [Code](image/code.png) you need to install.
1. Power the Uno board.
2. Unplug the 3.3v cable of the Esp module and plug it back in.<font color="red">The board is now in software installation mode!</font>
3. Start uploading your code.
4. Once installed, unplug the [GPIO-0](image/01_pin.png) pin.
5. Disconnect and reconnect the 3.3v cable of the Esp module.
