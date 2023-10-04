# Welcome to my github
I established this page in October 2023. Initially, I'll be uploading some of my older codes, which are primarily straightforward tasks. Unfortunately, many of my projects were developed for commercial purposes, and I can't share the actual code here. However, for a select few, I've received permission to share descriptions and screenshots. So, please note that not all projects will have the accompanying code.

I also plan to embark on some side projects and publish them here. I encourage you to check back occasionally for updates!

I'm a machine learning researcher with a deep passion for machine learning and computer vision. Contributed
to a university AI research group for three years and authored an article on Zika Virus detection in
mosquitoes. I hold a bachelor's in Control and Automation Engineering and am pursuing a master's in
Computer Science at Universidade Federal Fluminense. My career began in a machine learning startup;
now, I spearhead AI-driven solutions and lead digital transformation. Beyond AI, my technical expertise
extends to IoT, robotics, and automation. I’m consistently motivated by a relentless desire to innovate.

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/5b181360-0294-4fdf-9dd2-c68f01ce184d)

## Some projects

****************************************************************************************************************************************
### Using a neural network as a descriptor for keypoint extraction ( Comparing NN vs SIFT)

<b>Objective</b>

Compare keypoint descriptors and matches from 2 images of the same scene with different perpesctives using:

-SIFT descriptor and keypoint extractor + BF KNN Matcher

-NN Method 1: Neural Network (maxpool layers) descriptor + Keypoints extractor + BF KNN Matcher

-NN Method 2: Neural Network (maxpool layers) descriptor + Keypoints extracted from Sift + BF KNN Matcher

<b>Technologies and Tools</b>

Python, Computer Vision, Machine Learning

<b>Repository:</b> <a href="https://github.com/leoreigoto/Keypoint_Descriptor_Match">https://github.com/leoreigoto/Keypoint_Descriptor_Match</a>

Original images:

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/32aa97ac-6f01-41a7-b0fb-6172d3601409)

Descriptors from NN

The descriptors represents the squares from the images bellow. Initially there are 3 descriptors that are combined into one descriptors

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/b94760d5-256c-4104-b7f3-ae946de7db9f)

Results

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/c4e6d09e-7e0a-4602-977a-c85971bcc973)

****************************************************************************************************************************************
### Control of a 6-DOF Robotic Arm 

<b>Objective</b>

To integrate a SolidWorks model of a real-world robotic arm into a simulation environment. This project will derive and implement algorithms for the Kinematics, Inverse Kinematics, Dynamics, and Inverse Dynamics of the robotic arm, enabling accurate position and motion control.

<b>Technologies and Tools</b>

Matlab, Simulink, Robotics, Control and automation Engineering, PID Controller

<b>Repository:</b> <a href="https://github.com/leoreigoto/robotic_arm_6_DoF">https://github.com/leoreigoto/robotic_arm_6_DoF</a>

Inside the repository there are 2 version. One of them have the full project and the other one only contains the Forward Kinematics and trajectory planning (simpler approach).
I advice to simulate new tasks with the Forward Kinematics and trajectory planning before using the full version. It easier to debug this way.

<img src="https://github.com/leoreigoto/leoreigoto.github.io/blob/main/Robot_Arm.gif?raw=true" />

****************************************************************************************************************************************
### Image processing to enhance product serial number visibility 

<b>Objective</b>

Improve the clarity of product serial numbers to boost Optical Character Recognition (OCR) accuracy and reliability.

<b>Technologies and Tools</b>

Python, Computer Vision, OpenCV

The product serial numbers are inscribed in green letters on a transparent liquid. To heighten the contrast, a red light — complementary to green — was employed. Various image processing techniques were then applied to further amplify the visibility of the letters under the red light, ensuring effective OCR readings.

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/e9980faf-5bda-432d-a30c-c8b85bf7bf3f)


![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/453c9ad5-174e-4fd8-85df-63a69d20d01b)


****************************************************************************************************************************************
### Automated Conveyour Machine to OCR products serial number

<b>Objective</b>

To design and prototype an autonomous conveyor belt system that can effectively read product serial numbers using Optical Character Recognition (OCR).

<b>Technologies and Tools</b>

Computer Vision, Automation, Engineering, Python, Ladder & PLC, IoT, Modbus (a communication protocol used to establish a connection between the PLC and computer vision software)

Successful reading:

<img src="https://github.com/leoreigoto/leoreigoto.github.io/blob/main/ezgif-5-896300f6f4.gif?raw=true" />

Reading error (alarm signal and stops the conveyour belt)

<img src="https://github.com/leoreigoto/leoreigoto.github.io/blob/main/ezgif-5-be0d9822ef.gif?raw=true" />

Some functions:

<img src="https://github.com/leoreigoto/leoreigoto.github.io/blob/main/ezgif-5-a74f56d3c2.gif?raw=true" />

****************************************************************************************************************************************
### Detection of Zika Virus infection on mosquitoes using machine learning and spectroscopy

<b>Objective</b>

Predict Zika Virus on mosquitoes using spectroscopy wavelenghts from 350nm to 1000nm

<b>Technologies and Tools</b>

Python, Machine Learning, Signal Processing

<b>Repository:</b> <a href="https://github.com/leoreigoto/ZikaVirusDetection">https://github.com/leoreigoto/ZikaVirusDetection</a>


![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/a378a2af-7fed-416c-ba73-1579ff736d0c)

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/764bfe7c-0de1-4690-8aa2-a996bb3da6d8)

****************************************************************************************************************************************
### Anomaly detection with GAN and autoencoders for tabular data

<b>Objective</b>
TO_DO

<b>Technologies and Tools</b>

Python, Machine Learning, GAN

<b>Repository:</b> TO_DO

****************************************************************************************************************************************
### OCR on a Tesla dashboard to monitor veihicle fleets

<b>Objective</b>

To develop a real-time monitoring system for fleet management by capturing and analyzing critical data from a Tesla vehicle's dashboard using Optical Character Recognition (OCR). This system aims to ensure safe driving practices, efficient fleet operations

Tracks: Current vehicle speed, maximum permissible speed for the road, estimated battery longevity, Auto-pilot status (on/off).

<b>Technologies and Tools</b>

Python, Computer Vision, OpenCV, Websocket

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/f580dab0-7aff-45b9-ab27-4f30b02da133)

****************************************************************************************************************************************
### Machine Learning Model for Obesity Level Prediction

<b>Objective</b>

Develop a toy machine learning model to predict levels of obesity based on a publicly available dataset. This model aims to demonstrate the potential of machine learning in assessing health risks and guiding preventive measures.

<b>Technologies and Tools</b>

Python, machine learning, classification task

<b>Repository:</b> <a href="https://github.com/leoreigoto/ObesityPrediction">https://github.com/leoreigoto/ObesityPrediction</a>

The dataset uses SMOTE technique to increase it's data without giving the original data. This isn't advisable because it generates the following issues:

TO_DO

****************************************************************************************************************************************

### Machine Learning Model for Estimating Student Attrition Risk Percentage

<b>Objective</b>

To develop a toy machine learning model that estimates a student's risk percentage for attrition, assisting educational institutions in taking proactive measures to retain students.

<b>Technologies and Tools</b>

Python, machine learning, classification task

<b>Repository:</b> <a href="https://github.com/leoreigoto/student_evasion">https://github.com/leoreigoto/student_evasion</a>


****************************************************************************************************************************************
### Object detection

<b>Objective</b>

To develop a machine learning model capable of detecting and identifying multiple objects.

<b>Technologies and Tools</b>

Python, computer vision, machine learning, YOLO

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/bd924460-6255-4a0e-837c-8bee87feb0b0)

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/e3d715ad-3a0b-47da-9c18-baafb7897023)

****************************************************************************************************************************************
### Automation of an aquaponic system

<b>Objective</b>

To design and implement an automated aquaponic system, aiming to optimize resource utilization, improve system efficiency, and streamline the cultivation of both plants and aquatic organisms.

<b>Technologies and Tools</b>

C/C++ , IoT, Arduino, Automation, Engineering

<b>Repository:</b> <a href="https://github.com/leoreigoto/aquaponic_system_automation">https://github.com/leoreigoto/aquaponic_system_automation</a>

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/4b2fc07e-a0b4-48c9-8f27-02b97eaa050f)

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/9f2ea1d6-e177-4228-8eb0-1088f54bfe4f)

****************************************************************************************************************************************
### SQL client (sqlite + Tkinter)

<b>Objective</b>

To create a simple SQL client that integrates SQLite for backend database management and Tkinter for frontend GUI development. This project serves as an exercise in practicing SQL queries and leveraging Tkinter as a tool for developing lightweight applications.

<b>Technologies and Tools</b>

Python, SQL, Tkinter

<b>Repository:</b> TO_DO


