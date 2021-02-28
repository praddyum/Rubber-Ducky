# Rubber-Ducky

## What is this?

A Rubber Ducky is simply a device(generally USB) which is programmed such that it behaves like a human interface device (HID) for ex: Keyboard. This vulnerabiliy enables an attacker to create a payload and store it in the Rubber Ducky device and whenever it get conneced to a host, it will execute the preprogrammed payload on the host and perform malicious actions like providing backdoors ,installing viruses and malwares, retrieving the saved passwords etc.

## What is required?

1.  Choosing the Hardware Device
    - Aurdino
    
      Since we'll be using mouse and keyboard libraries so only `Leonardo`, `Micro` and `Due` boards can be used as they are the one who support these libraries.
      
    - Ruber Ducky from Hak5 - [Link](https://shop.hak5.org/products/usb-rubber-ducky-deluxe)

2.  Payload Script
    - [Aurdino IDE](https://www.arduino.cc/en/software) in case we are using Aurdino as our device
    - Example Scripts - [Link](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads)
    - [Aurdino Script Generator](https://techchip.net/ducky/) in case we using Aurdino as our device
 
 ## What I did in this project?
 
 Here we have created a Rubber Ducky script for aurdino based boards( Leonardo, Micro, Due). It creates a netcat reverse shell.
