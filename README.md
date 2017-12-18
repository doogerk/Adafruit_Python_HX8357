Adafruit Python HX8357
=======================

***Please note that this is an exact copy of Adafruit_Python_ILI9341 with slight changes to match the HX8357 library used for Arduino. I am not sure if this will actually work, as I have not tried it yet.

Python library to control an HX8357 TFT LCD display.  Allows simple drawing on the display without installing a kernel module.

Designed specifically to work with the Adafruit 3.5" LCD's ----> https://www.adafruit.com/products/2441

For all platforms (Raspberry Pi and Beaglebone Black) make sure you have the following dependencies:

````
sudo apt-get update
sudo apt-get install build-essential python-dev python-smbus python-pip python-imaging python-numpy
````

For a Raspberry Pi make sure you have the RPi.GPIO library by executing:

````
sudo pip install RPi.GPIO
````

For a BeagleBone Black make sure you have the Adafruit_BBIO library by executing:

````
sudo pip install Adafruit_BBIO
````

Install the library by downloading with the download link on the right, unzipping the archive, navigating inside the library's directory and executing:

````
sudo python setup.py install
````

See example of usage in the examples folder.

Adafruit invests time and resources providing this open source code, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Written by Tony DiCola for Adafruit Industries.

MIT license, all text above must be included in any redistribution
