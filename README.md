# Listening-bluetooth-music-using-cisco-packet-tracer
## Software Requirements for Development and Implementation
Platform :  Cisco Packet Tracer   

Operating  System: Windows/Mac

Programming Language: Java

## Introduction:
The terms "Internet of Things" and "Internet of Everything" allude to the new trend of using small, inexpensive, and always-connected devices to communicate data to backend cloud-based applications. This opens up a whole new world of possibilities and products for businesses to develop and sell in both the industrial and consumer markets. One of the most common uses of an IoT gadget is to listen to bluetooth music through a speaker.
Ericsson designed Bluetooth to allow users of wireless headphones to connect to a variety of devices. We can now use Bluetooth to connect to almost any electronic item, including speakers, headphones, car stereo systems, wearables, game controllers, printers, medical equipment, and more. Bluetooth technology has progressed from basic Bluetooth to smart Bluetooth, with the most recent version being Bluetooth 5. Bluetooth 5, for example, has four times the range, double the speed, and an 800% increase in data transmission frequency.
## Working Principle:
Bluetooth and IoT are inextricably linked, especially given the rate at which IoT is gaining traction and acceptance on a worldwide basis. It connects devices with minimal power, low range, and high bandwidth. It relates with a parent-child model. This implies that one device, such as your smartphone, serves as the parent, while the wireless speaker to which you're connected serves as the child. The information is pushed to the child by the parent's device, and the child "listens" for the information from the parent. So, if you're listening to music on your phone and want to listen to it on the speaker instead, you use Bluetooth to connect the two devices.
It is possible for a Bluetooth parent to have up to seven children. Bluetooth is used to connect a variety of devices such as a mouse, keyboard, speakers, printers, and more. A "piconet" is a network of interconnected electronics. It is so versatile that the parent gadget could be a child gadget in another piconet and vice versa.
## Why bluetooth is used with IoT devices:
Bluetooth excels in connecting two devices that require minimal configuration because it was built to work with portable equipment, devices, and applications. It also communicates with such devices at maximum efficiency even in a "noisy" environment by using weak signals. It's ideal for usage with Industrial IoT devices that deliver short data packets in noisy situations because of this.
## Why should bluetooth be considered as an IoT device:
Bluetooth is a flexible means of communicating in "noisy" regions at a low bandwidth. It's a strong tool when connected to IoT devices and utilised indoors, especially in asset management circumstances like a warehouse, where beacons (small Bluetooth Low Energy (BLE) devices that emit a radio signal that can be read by any smartphone) can communicate with one another. It's simple to set up, and when connected with other IoT devices, it creates a secure, self-healing network.
## How Bluetooth Enhances the IoT Architecture:
The hardware, communication, software system, and application layers make up a typical IoT design, with Bluetooth serving as the communication layer. The communication layer, which consists of a multi-layer stack that includes data connection, network or transport, and session protocols, is a vital link between the layers. Bluetooth, often known as BLE, is a data communication layer that links sensors to sensors or sensors to gateways. On the other side, the network layer is in charge of routing or transporting packets across the network using the most appropriate pathways. The session layer protocols allow communication between different aspects of the IoT communication subsystem.
'Bluetooth technology' is less expensive to implement than other communication protocols such as RFID, NFC, WLAN, LoRa WAN, LTE-A, and WiFi-Direct. It also allows for wireless communication and the creation of an immediate Personal Area Network (PAN) in areas where wireless infrastructure is lacking. It features a consistent methodology and minimum interference.

## Project using cisco packet tracer:
![p](https://user-images.githubusercontent.com/86556654/143622349-e1bc047a-4337-447d-b1a7-b9b2a4c6b9de.PNG)
## Steps for directly connecting music player to the bluetooth speaker:
Step 1: Choose a portable music player and pair it with the bluetooth speaker. The green horizontal lines indicate that the device is paired with the bluetooth speaker.

Step 2: Open the programming tab, and type in the required code.

Step 3 : Enable the Portable Music Player by pressing ALT-click.

Step 4 : The Portable Music Player will then send data to the Bluetooth Speaker through Bluetooth to play music.
![q](https://user-images.githubusercontent.com/86556654/143622533-b81ac1d5-2630-4de0-bb97-ee3e00b9b712.PNG)

## Steps for connecting music player to the bluetooth speaker via a smartphone :
Step 1 : Two devices are required - home gateway device and a smartphone. 

Step 2 : Change the IoT Server of  Music Player to Home Gateway under the config tab.

Step 3 : Change SSID of Music player to Home Gateway (SSID of home gateway device).

Step 4 : Open the IoT Monitor of smartphone and copy the ip address of home gateway to IoT Server Address to login.

Step 5 : The device that is connected to the gateway is displayed.

Step 6 : Click on the connected device and switch it on.

Step 7 : The music is now played from the music player which is operated by the smartphone.
![r](https://user-images.githubusercontent.com/86556654/143622682-0c5b0a37-9b94-4732-bda4-cb930131132c.PNG)

## State Chart Diagram:
![dg](https://user-images.githubusercontent.com/86556654/143617153-ee543c4b-a640-4844-87bf-42e509ffea9c.PNG)
## Use Case Diagram:
![an](https://user-images.githubusercontent.com/86556654/143617266-c70cf502-e14c-4086-9905-fee4a97f4a75.PNG)

## Results:
A bluetooth speaker is successfully connected and we can listen to the music via portable music player. Also, portable music player was accessed through a smartphone. The complete project is implemented using Cisco Packet tracer Environment. This mini project can be very useful and is user friendly to listen music with a portable music player which inturn could be operated from  a remote cellular device.
