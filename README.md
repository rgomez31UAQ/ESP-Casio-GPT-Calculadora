# esp-oled-firebase-Integration
0.91" inch OLED and a esp8266-12E, which is integrated to firebase to fetch text file and send and receive text message.
Para hackear su calculadora Casio modelo fx-991MS, Neutrino aprovechó la ranura donde se asienta el pequeño panel solar que sirve para alimentar esta calculadora. 
En su lugar, instaló un panel OLED que, apagado, tenía el mismo aspecto que la placa solar original. 
Para que la calculadora siguiera funcionando, instaló una batería recargable y un módulo wifi ESP8266 ESP-12E

### Getting Started

Clone the repo, open with arduino IDE [Tested on Arudino IDE 1.8.10 above]

### Prerequisites

Arduino Libraries for WIFI, JSON, Firebase and Mulit-Tap funtions

* [ESP8266](https://github.com/esp8266/Arduino) -ESP8266 core
* [Arduino JSON](https://github.com/bblanchon/ArduinoJson) - by bblanchon
* [Firebase](https://github.com/mobizt/Firebase-ESP8266) - by mobizt
* [OneButton](https://github.com/mathertel/OneButton) - by mathertel

### Installing

Open the Arduino IDE and follow the below steps:
```
Sketch -> include library -> ManageLibrary -> *Search for the above library*
```
Or
follow the instructions on respective library repository.

### Errors

4 Errors has been planted and extremely easy to fix! Compile once to figure out the Errors.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
