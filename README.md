<h3 align="left">Directory</h3>

<h4 align="left">GUI</h4>
<ul>
<li><a href="https://github.com/QuantumRoboticsURC/Web_Interface">Web Interface</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/QuantumRoboticsApp">Mobile App</a></li>
	
</ul>
<h4 align="left">Navigation</h4>
<ul>
<li><a href="https://github.com/QuantumRoboticsURC/ros_imu_bno055">imu_bno055</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/ublox">ublox_gps</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/qr_navigation">qr_navigation</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/nav_dif">nav_diff</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/simple_drive">simple_drive</a></li>
</ul>
<h4 align="left">Robotic Arm</h4>
<ul>
<li><a href="https://github.com/QuantumRoboticsURC/qr_arm_control">Robotic Arm</a></li>
</ul>
<h4 align="left">Vision</h4>
<ul>
<li><a href="https://github.com/QuantumRoboticsURC/zed-ros-wrapper">zed ros wrapper</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/zed-ros-examples">zed ros examples</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/usb_cam">usb cam</a></li>
<li><a href="https://github.com/QuantumRoboticsURC/Zed-implementations.git">zed implementations</a></li>
</ul>
<h4 align="left">Custom configuration</h4>
<ul>
<li><a href="https://github.com/QuantumRoboticsURC/custom_messages">custom messages</a></li>
</ul>

<details>
<summary><h3>Guidelines</h3></summary>
<h4> Branches </h4>
When you work with code along other developers, a branch shall be created, the structure for the branch must be the following:
<br><b>{firstLetterYourName}{firstLastName}/{BriefDescription}</b><br>
For example, Ariadna Huesca Coronado is working in a publisher of a coordinate so the name of the branch should be:
<br><b>ahuesca/coordinate_publisher</b>
<h4>Header</h4>
<p>Every file that contains code must contain a header with the following structure:</p>


```
Made by:Raul Lopez Musito
	A01378976@tec.mx
	raulmusito@gmail.com

Modified (DD/MM/YY): 
	Raul Musito 28/06/2022 Correct a bugg at the number of line write at 
				the csv file.
	Raul Musito 03/06/2022 Created the program

Code description:
1. Ask the user for the name of a file.
2. If the file exist at a predefined directory it opens it and read it.
   If not, it creates a file with the name.
3. Ask the user the action to execute (write lat & long | write the square).
4. Close the file. 

Notes:
- Validate the user input
- Add an exit option
* Despite the code adds 0.00001 theorically, it's not exact.
```
</details>
