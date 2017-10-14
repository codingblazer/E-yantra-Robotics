# E-yantra-Robotics

Hazardous Waste disposal using FireBird-V robot under a program organised by IIT-Bombay. We worked on this project for 6 months under guidance of IIT faculty.

Aim : The Robot has to detect the waste blocks using their colors (using colot sensors) and lift them and drop them at their respective location i.e. segregate waste blocks by their color. The Robot must follow the black line and will have to cross the wooden bridge in its path. The orientation of bridge has to be changed by placing weight blocks.

Thus, we needed shortest time algorithm to sort the waste blocks and put them at their correct location while maintaining black line path and algorithm for crossing bridge by using not more than 3 weight blocks.

We had to complete the task assigned to us before given deadline. Some of the work done by my team is as follows :

1) Setting Up the FireBird-V Robot, AVR Bootloader which is used to load code into the robot, Atmel Studio IDE for writing code in Objective-C. Also we had to setup the arena sheet (flex sheet) on which robot will run, making weight blocks, making colored waste blocks, Building a wooden bridge, etc.

2) Designing and Building a Robotic arm. The challenge was to develop the arm which can lift weights upto 200 gms. Along with lifting and droping mechanism, a color sensor was to be positioned to detect the colors of waste blocks. It was most challenging task as we had to code proper algorithm for changing angles based on trignometric calculations. 

3) An algorithm to follow the black line for which we were given Black and white line sensors, proximity sensors, etc.

4) An algorithm for crossing the bridge by using only given weights.

5) An algorithm to detect the colors of boxes using Color sensors, an algorithm to lift a certain block which needed to set a combination of angles of 3 servo motors of robotic arm based on trignometric calculations. Further placing them at their correct position.

Below is the small demonstration of work done :


![ezgif com-optimize](https://user-images.githubusercontent.com/13872065/31575122-118b080a-b0fd-11e7-934a-6bc8b1444945.gif)

