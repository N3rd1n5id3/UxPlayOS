
# UxPlayOS
## A simple Raspberry Pi OS with UxPlay service

#### Flash Raspberry Pi OS 64-bit Lite with Raspberry Pi Imager.
#### Install the Official PIXEL Desktop:
```diff
sudo apt install xserver-xorg raspberrypi-ui-mods
```
#### Install UxPlay:
```diff
sudo apt install uxplay
```
#### Download UxPlay Service:
```diff
wget bit.ly/uxplay_service
```
#### Copy UxPlay Service in systemd:
```diff
sudo cp uxplay_service /etc/systemd/system/UxPlay.service
```
#### Enable UxPlay Service:
```diff
sudo systemctl enable UxPlay.service
```
#### Start UxPlay Service:
```diff
sudo systemctl start UxPlay.service
```
#### Boot into CLI permanently:
```diff
sudo raspi-config
```
System Options > Boot / Auto Login > Console Autologin