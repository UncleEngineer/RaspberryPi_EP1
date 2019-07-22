# RaspberryPi_EP1
RaspberryPi_EP1

Youtube: https://www.youtube.com/watch?v=FF0zjOQxlP4


Raspberry Pi 3 - Step by Step

1- Goto https://www.raspberrypi.org/

2- โหลดหนังสือเล่มนี้ https://www.raspberrypi.org/magpi-issues/Beginners_Guide_v1.pdf

3- หนังสือรวมโปรเจค https://www.raspberrypi.org/magpi-issues/Projects_Book_v1.pdf

https://www.raspberrypi.org/magpi-issues/Projects_Book_v2.pdf

https://www.raspberrypi.org/magpi-issues/Projects_Book_v3.pdf

https://www.raspberrypi.org/magpi-issues/Projects_Book_v4.pdf

4- Download: Raspbian Image (OS ของ RasbperryPi)

5- Download [Raspbian Buster with desktop and recommended software]  zip file

6- Donwloand: SDCard Formatter , Win32 Disk Imager

7- Format MicroSDCARD with SDCard Formatter

8- Win32 Disk Imager > Load .img > Write

9- Insert microsdcard to Raspberry Pi

10- Connect HDMI, Mouse, Keyboard and connect USB Power 

11- Goto terminal: sudo apt-get install xrdp สำหรับใช้ remote เข้าไปใช้งาน Raspberry Pi

12- goto terminal > sudo raspi-config
	- Interfacing Option
	- SSH to Enable (yes)
	- VNC to Enable (yes)
	- Finish

13- Check IP: เอาเมาส์ไปคลิกตรงโลโก้ WiFi หรือ
	- sudo ifconfig
	- ดูตรง wlan0

14- Remote Desktop > ใส่ ip: 192.168.0.xxx 
	- USER: pi 
	- Password: raspberry






