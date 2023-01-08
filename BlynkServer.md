# Blynk server
Blynk Server is an Open Source Java server, responsible for forwarding messages between Blynk mobile application and 
various microcontroller boards (i.e. Arduino, Raspberry Pi. etc).

Server source code and official binaries released by [Blynk](https://www.blynk.io) at `https://github.com/blynkkk/blynk-server` were deleted around September 2022

[Here](https://github.com/gablau/blynk-server-binaries) you can find a mirror of the server binaries that I had previously backed up.

Latest binary is version [0.41.17](https://github.com/gablau/blynk-server-binaries/tree/master/0.41.17)

## Server source code mirror

A fork of the source code can be found here: [https://github.com/gablau/blynk-server](https://github.com/gablau/blynk-server)

## Why do I need Local Blynk Server?

- Better security. You are the only one who knows about the server. You can setup security policies tied to your specific needs (MAC, IPs, login names, etc). You can also make it accessible only within your private network.
- Better stability. No need to rely on 3rd party Cloud solution. You have the full control.
- Lower latency. Server is as close to you as it could be. 
- Maximum privacy. All data is stored locally and is not shared with anyone.

## Installing your own Local Blynk Server

For detailed instruction please follow [github page](https://github.com/gablau/blynk-server#blynk-server).