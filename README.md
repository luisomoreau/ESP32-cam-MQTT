# Get started with the ESP32 cam module and store pictures in the Cloud

In this tutorial, we will see how to take a picture publishing a message on a SMILE topic and forward this message to an S3-compatible Object Storage bucket.

![diagram](assets/diagram.png)

To do this, we will be using the default example code for the esp32 camera module which will be slightly modified to add the MQTT compatibility.

## Material

![esp32-cam](assets/esp32-cam.jpg)

Get the boards:

* [Aliexpress](https://fr.aliexpress.com/item/1005001900359624.html)
* [Amazon](https://www.amazon.fr/diymore-d%C3%A9veloppement-Bluetooth-ESP32-CAM-MB-Dual-core/dp/B08P1NMPLL)

The external antenna is optional but will give you a better Wifi coverage

## Prerequisties

- Having a [Scaleway account](https://console.scaleway.com/)
- Download or clone this repository: [https://github.com/luisomoreau/ESP32-cam-MQTT](https://github.com/luisomoreau/ESP32-cam-MQTT)
- Download and install the Arduino IDE: [https://www.arduino.cc/en/main/software](https://www.arduino.cc/en/main/software)

![arduino-installer](assets/arduino-installer.png)


## Setting up environment

Open Arduino preferences:

![arduino-preferences](assets/arduino-preferences.png)

and add the board `https://dl.espressif.com/dl/package_esp32_index.json` as followed:

![arduino-preferences](assets/arduino-preferences.png)

Go to your board manager:

![board-manager-menu](assets/board-manager-menu.png)

And add the offical Espressif boards:

![board-manager](assets/board-manager.png)

Select the AI Thinker ESP32-CAM:

![select-board](assets/select-board.png)

## Creating a hub




## Going further

Here is some interesting readings if you'd like to deep dive into the subject:

* [https://randomnerdtutorials.com/upload-code-esp32-cam-mb-usb/](https://randomnerdtutorials.com/upload-code-esp32-cam-mb-usb/)
* [https://github.com/easytarget/esp32-cam-webserver](https://github.com/easytarget/esp32-cam-webserver): More advance code that can be easily modified (including the html part)
* [ESP32 CAM Face Recognition With MQTT Support](https://www.instructables.com/ESP32-CAM-Face-Recognition-With-MQTT-Support-AI-Th/)