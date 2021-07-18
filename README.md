# VoiceTurn - Voice-controlled turn lights for a safer ride

### Arduino library of the VoiceTurn project (Arduino Nano 33 BLE Sense required)
- Project website
- [Edge Impulse project](https://studio.edgeimpulse.com/public/39038/latest)
- YouTube video

#### Instructions:
[Install the Arduino IDE](https://www.arduino.cc/en/software)

From the Arduino IDE, click on `Tools > Board > Boards Manager...` and install the **Arduino Mbed OS Nano Boards** package.

Plug the Arduino board to one of the USB keys of the computer.

Click on `Tools > Board > Arduino Mbed OS Nano Boards` and select **Arduino Nano 33 BLE Sense**.

Click on `Tools > Port` and choose the serial port the Arduino board is connected to.

Click on `Sketch > Include Library > Manage Libraries...` and install the **Adafruit NeoPixel** library.

To add the VoiceTurn library to the Arduino IDE, there are two options available:
- Click on `File > Preferences` to obtain the Sketchbook location path and clone the repository into **$[path]/libraries/**
- Download the repository as a .zip file and add it to the Arduino IDE through `Sketch > Include Library > Add .ZIP Library...`

Click on `File > Examples > VoiceTurn_inferencing > voiceturn` to open the main program.

Compile and upload the program by clicking on the two buttons on the top left corner of the Arduino IDE.

Open the serial monitor by clicking on the button on the top right corner of the Arduino IDE and verify the output predictions.

Disconnect the Arduino board from the computer.

Connect the VoiceTurn hardware to the Arduino board.

Install it on a bicycle.

Connect the Arduino board to the power bank.

Enjoy the ride!
