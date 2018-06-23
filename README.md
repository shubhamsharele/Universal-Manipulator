# Universal-Manipulator
# Abstract

A mechanical arm, programmable with similar functions to a human arm having. The gripper attached can be used to pick objects from one  given coordinates and drop to another given coordinates .

# Team Members
<li>Vipin Kumar</li>
<li>Shubham Kumar</li>
<li>Amit Kumar</li>
<li>Shivam Chopra</li>
<li>Punit Gora</li>

# Mentors
<li>Bhaskar Kaushik</li>
<li>Shivam Srivastava</li>

# Applicatioins

Robotic arms are typically used for industrial applications. The application is the type of work robot is designed to do.
Different applications will have different requirements. Industrial robots are designed for specific applications and based on their function will have their own movement, linkage dimension, control law, software and accessory packages. It can be used for welding, painting, palletizing.

# Hardware
<ol>
  <li>Base</li>
  
<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/base.png"></div></p>  
  
 <li>Base gear</li>
  
<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/gear.png"></div></p>  
 
 <li>3D printed arms</li>

<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/arm.png"></div></p>

<li>Controling gears</li>

<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/3D-printed-Gear-set-for-prototyping-with-plastic-.jpg"></div></p>

<li>bearings</li>

<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/24007914_962347590582031_479002411_o.jpg"></div></p>

<li>worm gear</li>

<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/download.jpg"></div></p>

<li>Arduino Uno</li>
<li>Rotary Encoders</li>
<li>High torque dc motors(12 volt)</li>
<li>Motor driver(LN298N)</li>
<li>Servo motor for gripper</li>

</ol>
# Software

<b>arduino:</b>
The movement of dc motors and the servo motor is controlled by the arduino code with the help of the feedback from the rotary encoders.

# Structure
The bot is made by joining 2 arms with base gear along with a gripper. DC motors are attached with arms and base gear to provide  motion. The whole structure is mounted on a wooden base. The 3D printed base is fixed with wodden base on which base gear is mounted using bearing. DC motor is attached to base gear using the controling gears along with the encoder. One arm is mounted on the base gear using shaft and bearings along with DC motor and rotory encoder.Worm gear is attached to the controlling gear to lock the arm at certain position and prvent the 2nd arm from falling. 2nd arm is mounted on the 1st arm along with DC motor and encoder.At the end of 2nd arm gripper is fixed. Servo motor is attached to the gripper to hold an object.

<p><div><img src="https://github.com/shubhamsharele/Universal-Manipulator/blob/master/Photos/DSC_0085.NEF.jpg"></div></p>


# Working
Basically initial and final coordinates are fixed.The sequence of steps followed are also fixed but can be varied using code. Initally one arm will go down and the gripper will grab the object using servo motor. Then the 2 arms will move up and base gear will rotate to another coordinates as given in the code. Then it will drop the object. Finally the the arms and base gear will come to their initial location. The initial and final coordinates can be varied using the code.

# Limitations and Future Improvements
<ol>
<li>It can only pick object from fixed coordinate and drop it to another fixed coordinate. The coordinates can be only be varied from code. Image processing can be used to detect the positioin of the object.<li>
<li>The size of object is also fixed. It should also be able to pick the object of various sizes.</li> 
</ol>
    
# Video
https://photos.app.goo.gl/8jrEAZFpoxkNe4iW9
