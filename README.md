# raspberry-pi-devices
Notes on Raspberry Pi Devices

* [upgrade raspberry pi OS steps](https://www.raspberrypi.com/documentation/computers/os.html)

## Mini Router
![IMG_0654](https://user-images.githubusercontent.com/58792/174637418-c427ac34-c0e0-4d9f-b455-9f09fd2c93d1.jpg)
![Screen Shot 2022-06-20 at 12 35 12 PM](https://user-images.githubusercontent.com/58792/174646091-aef9b75d-cf52-4df7-b7ce-bb162f66f82a.png)

* [login to openwrt](https://openwrt.org/docs/guide-quick-start/walkthrough_login)

## reTerminal
![IMG_0655](https://user-images.githubusercontent.com/58792/174637421-336f5dce-8927-4ba8-9098-3f65ccff6fa5.jpg)

* [Getting Started](https://wiki.seeedstudio.com/Dual-Gigabit-Ethernet-Carrier-Board-for-Raspberry-Pi-CM4/)


## Edge Inference

* [Uses Coral AI](https://coral.ai/)

![IMG_0656](https://user-images.githubusercontent.com/58792/174684166-cae6c565-0b92-47d0-94b1-85d051d5ca52.jpg)

### Get Coral Running

1.  Upgrade OS [upgrade raspberry pi OS steps](https://www.raspberrypi.com/documentation/computers/os.html)
2.  Install Vim:  `sudo apt-get install vim`
3.  Install Git:  `sudo apt-get install git`
4.  SSH into your raspberry pi.
5.  Upgrade [Python to 3.9](https://stackoverflow.com/questions/64718274/how-to-update-python-in-raspberry-pi)
5. Follow guide from Coral to install [Edge TPU runtime](https://coral.ai/docs/accelerator/get-started/#requirements)
6. Since this is a lab experiment I chose maximum operating frequency (sudo apt-get install libedgetpu1-max)
7.  Go through "run a model" code [found here](https://coral.ai/docs/accelerator/get-started/#3-run-a-model-on-the-edge-tpu)





