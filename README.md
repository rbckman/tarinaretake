Tarina Retake
=============
Let's introduce this thing with a thing it made, [a film on youtube](https://youtu.be/Yl2oAxMtDV0?si=lXOYTpkJi1YFuO2u) !

Software
--------
- glue selected clips together and/or cutting them.
- making timelapses, voiceover, music track recording, slo-mo recording, fast-forward recording
- cut and copy and move clips around
- backup to usb harddrive or your own server
- upload or stream to youtube or your own server
- auto correction can easily be switched on or off for shutter, iso and colors so *operator* is in full control also for audio levels
- connect many Tarinas together for multicamera shooting
- stream a film a take or a scene through the network
- control the camera with silent physical buttons or a usb-wireless-keyboard or through https or ssh or ports, you choose.

### Buttons
![Buttons](/extras/buttons.png)

Installing
----------
Download [Raspbian buster (not the latest!)](https://www.raspberrypi.org/downloads/raspbian/) and follow [install instructions | a simple install script should take care of it all!](https://www.raspberrypi.org/documentation/installation/installing-images/README.md).
[Ssh into](https://www.raspberrypi.org/documentation/remote-access/ssh/) Raspberry Pi and run:
```
sudo apt-get install git
```
Go to /home/pi/ folder
```
cd /home/pi
```
Git clone Tarina Retake and then run install script with sudo:
```
git clone https://github.com/rbckman/tarinaretake.git
cd tarinaretake
sudo ./install.sh
```
You'r ready to rumble:
```
python3 tarinaretake.py
```

Connect
-------
Matrix [#tarina:matrix.tarina.org](https://riot.im/app/#/room/#tarina:matrix.tarina.org)

Mail rob(at)tarina.org

