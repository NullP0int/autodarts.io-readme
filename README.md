Due to many questions how to setup the cameras and the equipment I decided to write a quick tutorial.

## What is needed?

Of course if you want to start with autodarts.io you'll need a steel dartbaord. For a well working dart recognition you also need a 360 degrees led lightring so that the darts don't cast shadows. The cameras needs to have a good view on the baord. For that you need to find a way how the cameras can see the whole board. There are multiple ways to do that, for example attach them to the led ring. Because we want to caputre the darts you need three cameras. And last but not least you need a device where you can connect and control the cams. For that you can use a working computer with Linux running on it. You also can use a Rasbperry Pi or a NVIDA Jetson Nano.

## Camera adjustments

This is one of the parts where the most questions are about but due to a very stable codebase the setup is quite easy if you stick to the following rules.

- The cameras need to have a good view on the whole board.
- The lenses of the cameras need to have an angle of 35 to 55 degrees to the board surface
- The cameras need to have a distance of 120 degrees to each other

Which camera you are using does not matter too much. But one of the things where you should take care of is that the camera does not have any distortion. My setup is running on cams which have a field of view (FOV) of 65 degrees and they are 30cm far from the wall and have a distance to the bullseye of about 36cm. 

## Linux system setup



## Working setups
