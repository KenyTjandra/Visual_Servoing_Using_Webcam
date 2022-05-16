# Visual_Servoing_Using_Webcam

The aim of the project is to create an algorithm that could indicate where the camera should move following any random pattern or picture. In this case we are shifting a bit to show a better demonstration in which we keep the camera still and move the picture around. We created a red line to show the movement of the picture and created the output to tell us where to move the picture to reach the center. This includes the depth of the image although we are using the webcam camera instead of the Realsense from intel which allows us to tell depth of the image, we only check the radius of the circle and tell if the image is too close or too far from the camera. This is due to the limitations that we are unable to run pyrealsense on windows 11.

Basically, the objective of the code is to detect the image given (Green ball in our case) and track the ball as it moves around and create an output in which the goal is to put the ball back in its initial position (center).

 Starting off by creating a lower and upper boundary for the image (green ball) in order to detect the green ball. Keep on detecting the position of the green ball and check the position constantly. Following this step, we tried to find the extreme point (edge) of both x and y axis in order to determine the output whether to move right, left, up, or down. In addition, we also determine of the object is too close or too far from camera by checking out on the radius of the object. 

By applying those code, we can obtain a visual servoing although currently we are moving the picture instead of the camera, same fundamentals can be applied. 

And as for the contribution for the project and code, we pretty much do the same amount of work (50 – 50) as we are only a group of 2 and we don’t have anyone else to discuss with although we are unable to meet in person as we’re currently not in the same country.
