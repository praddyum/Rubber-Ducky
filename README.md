# Rubber-Ducky

## What is this?

A Rubber Ducky is simply a device(generally USB) which is programmed such that it behaves like a human interface device (HID) for ex: Keyboard. This vulnerabiliy enables an attacker to create a payload and store it in the Rubber Ducky device and whenever it get conneced to a host, it will execute the preprogrammed payload on the host and perform malicious actions like providing backdoors ,installing viruses and malwares, retrieving the saved passwords etc. To read more- [Visit](https://www.linux.org/threads/usb-rubber-ducky.4464/)

## What is required?

1.  Choosing the Hardware Device (Any of the two devices could be used just script will be changed)
    - Aurdino
    
      Since we'll be using mouse and keyboard libraries so only `Leonardo`, `Micro` and `Due` boards can be used as they are the one who support these libraries.
      
    - Ruber Ducky from Hak5 - [Link](https://shop.hak5.org/products/usb-rubber-ducky-deluxe)

2.  Payload Script
    - [Aurdino IDE](https://www.arduino.cc/en/software) in case we are using Aurdino as our device
    - Example Scripts - [Link](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads)
    - [Aurdino Script Generator](https://techchip.net/ducky/) in case we using Aurdino as our device

3.  Target Device
    - **Linux**
 
 ## What I did in this project?
 
 Here we have created a Rubber Ducky script to run command `rm -rf /` on a `linux` distribution and the script can be mounted over aurdino based boards( Leonardo, Micro, Due).

If you have more ideas feel free to contribute to this repo.
