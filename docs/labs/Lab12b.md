# Fast Robots @ Cornell

[Return to main page](../index.md)

# Lab 12: Inverted Pendulum

## Objective
_Congratulations!_ You have built a robot (Labs 2-4) with debugging capability (Lab 1) and closed loop control (Labs 5-7) that can perform amazing stunts (Lab 8). You've shown its ability to map its environment (Lab 9), and to localize within it (Labs 10-11). 

For your final lab, in lieu of performing path planning and navigation, you can flex your controls muscles and get your car to pop a wheelie! This lab is intentionally very open ended, we encourage creativity and you should feel free to tailor your solution to the system you have developed. Make sure your lab report describes what options you have considered and why you choose the methods you do.

For example, 
* Start the car in the upright position and build a closed loop controller that stabilizes the car around this stable point.
* Closed loop control: gains can either be hand-tuned or determined using optimal control theory.
* Estimation: is the IMU data reliable and fast enough for the stunt? Do you need to include the Kalman Filter?
* Start the car in the normal position, drive forward at speed and rapidly brake as if you are going to implement the flip. Start the controller mid-flip to maintain the wheelie position.

Two great examples from prior years are shown below:

Stephan Wagner:

[![Stephan Wagner](https://img.youtube.com/vi/ioA5IQkiZAE/0.jpg)](https://youtu.be/ioA5IQkiZAE?si=huBxrLQI_6XTCIq-)

Nita Kattimani, Aravind Ramaswami, Anunth Ramaswami:

[![Watch the Video](https://img.youtube.com/vi/WKfhfwsL8mU/0.jpg)](https://www.youtube.com/watch?v=WKfhfwsL8mU&t=8s)


We highly encourage collaboration, just be sure to credit your partners.
 
Please carefully document how well your solution, and all parts of it, works. This may include a brief introduction to the capabilities of your system, relevant code snippets, and a flowchart diagram of what processes (offboard/onboard) run when; how long each take to execute and how reliable/accurate the outcome is. Obviously, include a video of your robot working!

## Write-up
To demonstrate that you've successfully completed the lab, please upload a brief lab report (<1.500 words), with code (not included in the word count), photos, and videos documenting that everything worked and what you did to make it happen.
