# Heart Rate & IMU sensor data for fall detection (HIFD dataset)
This dataset was introduced in the published acticle, IEEE Access 2020, "Cluster-Analysis-based User-Adaptive Fall Detection using Fusion of Heart Rate Sensor and Accelerometer in a Wearable Device.".
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8970371

nhoyh1@gmail.com, yhnho@kaist.ac.kr, TCL, KAIST, http://robot.kaist.ac.kr

<img width="300" src="https://user-images.githubusercontent.com/42211418/82864732-2f738c80-9f60-11ea-9826-ffbfcd65a730.png">    <img width="300" src="https://user-images.githubusercontent.com/42211418/82864740-33071380-9f60-11ea-852a-0716d2dff93e.jpg">



Description
-----------
	1) Sensor attachment location: at a wrist (left hand)
	2) Subjects: 21 (13:male / 8: female)
	3) Sampling rate: 50 Hz
	4) 19 Scenarios: 6 falls, 9 ADLs, and 4 near-falls
	5) An Effectiveness of gravity is removed.
	6) A range of accelerometer: +-16g
	7) Heart rate signal is processed to easily obtain RR interval

Scenario
---------
	1) fall1.mat: Clockwise forward fall
	2) fall2.mat: Clocklwise backward fall
	3) fall3.mat: Right to left lateral fall
	4) fall4.mat: Counterclock-wise forward fall
	5) fall5.mat: Counterclock-wise backward fall
	6) fall6.mat: Left to right lateral fall
	7) bed.mat: Lying down and up on the bed
	8) chair.mat: Sitting down and up
	9) clap.mat: Hitting the sensor
	10) cloth.mat: Wearing a cloth
	11) eat.mat: Eating
	12) hair.mat: Brushing the hair
	13) shoe.mat: Tying a shoelace
	14) stair.mat: Climbing up and down on stairs
	15) teeth.mat: Brushing teeth
	16) walk.mat: Walking
	17) wash.mat: Washing
	18) write.mat: Writing
	19) zip.mat: Rapidly zipping up and down

Data notation
-------------
	1) ax: x axis of accelerometer signal (g)
	2) ay: y axis of accelerometer signal (g)
	3) az: z axis of accelerometer signal (g)
	4) w: quaternion of gyroscope
	5) x: quaternion of gyroscope
	6) y: quaternion of gyroscope
	7) z: quaternion of gyroscope
	8) droll: angular velocity of gyroscope
	9) dpitch: angular velocity of gyroscope
	10) dyaw: angular velocity of gyroscope
	11) heart: PPG sensor
	12) time: Real time 

Subject information (Age, Sex)
----------------------
	1) Subject1: 31, Male
	2) Subject2: 21, Female
	3) Subject3: 28, Male
	4) Subject4: 25, Male
	5) Subject5: 21, Female
	6) Subject6: 28, Male
	7) Subject7: 32, Male
	8) Subject8: 22, Female
	9) Subject9: 27, Male
	10) Subject10: 25, Male
	11) Subject11: 27, Male
	12) Subject12: 26, Male
	13) Subject13: 21, Female
	14) Subject14: 21, Female
	15) Subject15: 29, Female
	16) Subject16: 30, Male
	17) Subject17: 23, Female
	18) Subject18: 28, Male
	19) Subject19: 25, Male
	20) Subject20: 21, Female
	21) Subject21: 30, Male
