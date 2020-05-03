# TensorFlow_Lite_Pose_RPi_32-bits
TensorFlow Lite Posenet running at 5.0 FPS on bare Raspberry Pi 4

A fast C++ implementation of TensorFlow Lite on a bare Raspberry Pi 4.
Once overclocked to 2000 MHz, the app runs at 5.0 FPS without any hardware accelerator.

https://medium.com/tensorflow/real-time-human-pose-estimation-in-the-browser-with-tensorflow-js-7dd0bc881cd5 <br/>
Frame rate Pose Lite : 5.0 FPS (RPi 4 @ 2000 MHz - 32 bits OS) <br/>
Frame rate Pose Lite : 9.4 FPS (RPi 4 @ 1825 MHz - 64 bits OS) see https://github.com/Qengineering/TensorFlow_Lite_Pose_RPi_64-bits<br/>
<br/>
Special made for a bare Raspberry Pi see: https://qengineering.eu/install-tensorflow-2-lite-on-raspberry-pi-4.html <br/>
<br/>
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/TensorFlow_Lite_Pose_RPi_32-bits/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
Dance.mp4 <br/>
posenet_mobilenet_v1_100_257x257_multi_kpt_stripped.tflite <br/>
TestTensorFlow_Lite_Pose.cpb <br/>
Pose_single.cpp<br/>
 <br/>
Run TestTensorFlow_Lite.cpb with Code::Blocks. Remember, you also need a working OpenCV 4 on your Raspberry. <br/>
Preferably use our installation here: https://qengineering.eu/install-opencv-4.3-on-raspberry-pi-4.html <br/>

![output image]( https://qengineering.eu/images/Girl_5_0.png )

See the Ubuntu 9.4 FPS movie at: https://www.youtube.com/watch?v=LxSR5JJRBoI


