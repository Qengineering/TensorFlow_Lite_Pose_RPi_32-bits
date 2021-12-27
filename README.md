# TensorFlow_Lite_Pose_RPi_32-bits
![output image]( https://qengineering.eu/images/Girl_5_0.png )<br/>
## TensorFlow Lite Posenet running on a bare Raspberry Pi 4
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
A fast C++ implementation of TensorFlow Lite on a bare Raspberry Pi 4.
Once overclocked to 2000 MHz, the app runs at 5.0 FPS without any hardware accelerator.
Special made for a bare Raspberry Pi see: https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html <br/>

------------

Papers: https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5 <br/>

------------

## Benchmark.
Frame rate Pose Lite : 5.0 FPS (RPi 4 @ 2000 MHz - 32 bits OS) <br/>
Frame rate Pose Lite : 9.4 FPS (RPi 4 @ 1825 MHz - 64 bits OS) see https://github.com/Qengineering/TensorFlow_Lite_Pose_RPi_64-bits<br/>

------------

## Dependencies.<br/>
To run the application, you have to:
- TensorFlow Lite framework installed. [Install TensorFlow Lite](https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html) <br/>
- OpenCV installed. [Install OpenCV 4.5](https://qengineering.eu/install-opencv-4.5-on-raspberry-pi-4.html) <br/>
- Code::Blocks installed. (```$ sudo apt-get install codeblocks```)

------------

## Installing the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_Pose_RPi_32-bits/archive/refs/heads/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
Dance.mp4 <br/>
posenet_mobilenet_v1_100_257x257_multi_kpt_stripped.tflite <br/>
TestTensorFlow_Lite_Pose.cpb <br/>
Pose_single.cpp<br/>

------------

## Running the app.
Run TestTensorFlow_Lite.cpb with Code::Blocks.  More info or<br/> 
if you want to connect a camera to the app, follow the instructions at [Hands-On](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html#HandsOn).<br/>
See the Ubuntu 9.4 FPS movie at: https://www.youtube.com/watch?v=LxSR5JJRBoI

------------

[![paypal](https://qengineering.eu/images/TipJarSmall4.png)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CPZTM5BB3FCYL) 



