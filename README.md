# Welcome to my github
I'm a machine learning researcher with a deep passion for machine learning and computer vision. Contributed
to a university AI research group for three years and authored an article on Zika Virus detection in
mosquitoes. I hold a bachelor's in Control and Automation Engineering and am pursuing a master's in
Computer Science at Universidade Federal Fluminense. My career began in a machine learning startup;
now, I spearhead AI-driven solutions and lead digital transformation. Beyond AI, my technical expertise
extends to IoT, robotics, and automation. I’m consistently motivated by a relentless desire to innovate.

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/5b181360-0294-4fdf-9dd2-c68f01ce184d)

## Projects

<b> 1- Moving a ML model to production using MLFlow, Docker and Fastapi

<b> 2- Object detection with Detectron 2 and MLFlow (vehicle registration plate)

<b> 3-  Stock and Production Management System (C++ data structure project) </b>

<b> 4-  Using a neural network as a descriptor for keypoint extraction ( Comparing NN vs SIFT) </b>

<b> 5-  Control of a 6-DOF Robotic Arm  </b>

<b> 6-  Automated Conveyour Machine to OCR products serial number </b>

<b> 7-  Detection of Zika Virus infection on mosquitoes using machine learning and spectroscopy</b>

<b> 8-  OCR on a Tesla dashboard to monitor veihicle fleets </b>

<b> 9-  Machine Learning Model for Obesity Level Prediction </b>

<b> 10-  Machine Learning Model for Estimating Student Attrition Risk Percentage</b>

<b> 11- SQL client (sqlite + Tkinter)</b>

****************************************************************************************************************************************
### Moving a ML model to production using MLFlow, Docker and Fastapi


<b>Objective</b>

- Deploy a machine learning model in production using Fastapi, Docker and Mlflow.
- Make an automated pipeline to prepare data, train the model and track model versions with mlflow
- Make an API for prediction using Fastapi. The API can run independently with a local model or in integration with mlflow
- The API and mlflow server with the training pipeline should run in different docker containers.
- In case of integration with mlflow, the API will check for newer versions of the model (with production tag on mlflow) and load it automaticallu 
- The code is hightly modular and scalable and the github repository contain instructions of how to personalize it
- All functions and modules should be well documented

<b>Technologies and Tools</b>

Python, Machine Learning, MLOps, sklearn, docker, fastapi, mlflow

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/59845023-35aa-48e5-8702-e53b9c00004c)


<b>Repository:</b> <a href="https://github.com/leoreigoto/House_Price_API">https://github.com/leoreigoto/House_Price_API</a>


****************************************************************************************************************************************

# Object detection with Detectron 2 and MLFlow (vehicle registration plate)

Objective:
- Train an algorithm to detect vehicle registration plate using detectron 2 and share training logs with MLFlow

Technologies and Tools:
SSD, Detectron 2, RetinaNet, MLFlow, Pytorch

Detection Video:

[![Vehicle plate detection_video](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/e7ab4286-7482-40ef-9bab-8d50b6fddc2f)](https://youtu.be/2uCMVJ7B49E?t=2 "Vehicle plate detection_video")


Mlflow logs:

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/5311a9f9-c2bd-41e5-89ad-060135acbacd)

https://dagshub.com/leoreigoto/Object_Detection_Vehicle_Plate.mlflow

Drive Files:

https://drive.google.com/drive/folders/1j1-oKIcoQC7N5lT8SDOnHBiBxDZ21q5C

<b>Repository:</b> <a href="https://github.com/leoreigoto/Object_Detection_Detectron2_MLFlow">https://github.com/leoreigoto/Object_Detection_Detectron2_MLFlow</a>


****************************************************************************************************************************************
### Stock and Production Management System (C++ data structure project)

<b>Objective</b>

Create a system that uses queue and deque structures to manage a factory and automate the creation of manufacturing orders based on branches stocks levels. The ideia its that this system could be used alongside readings from systems like RFID as a middleware before sending the data to an ERP. This would be an open-source replacement to RFID suppliers middlewares and would be highly scalable and easy to personalize with new funcionalities for each specific business (ie: on the proejct is implemented the system to generate manufacturing orders based on stock levels and management of production station queues)

<b>Technologies and Tools</b>

C++, data structure

<b>Repository:</b> <a href="https://github.com/leoreigoto/Production_and_stock_management_system/">https://github.com/leoreigoto/Production_and_stock_management_system/</a>

The repository contains :
- english version of the code
- video in portuguese explaining the project
  
 TO DO: translate it (this video was done for a discipline in my masters course)
 
[![Stock and Production Management System](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/69031dd7-e11c-495d-8539-698568b8f626)](https://youtu.be/Y4ufX6tZl0U?t=184 "Stock and Production Management System")

- article in portuguese explaining the project

TO DO: translate it

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

In the context of this project, the descriptors represent each square marked in the image below. Initially there are 3 descriptors that are combined into one.

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/b94760d5-256c-4104-b7f3-ae946de7db9f)

Results

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/ad240ddf-25d0-4031-a7ab-d8d094fb6556)


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
The repository contains: dataset and code.

<b>Issues in the dataset:</b>

The dataset utilizes the SMOTE technique to augment its data and doesnt share the original data. The SMOTE process was applied prior to dividing the data into training and test sets. This renders the dataset unreliable for practical use as it leads to <b> data leak </b>.

<b>Data leak</b> occurs because SMOTE uses different data to generate a new data point by interpolating between the 'parent' data points. We could have the <b>'parent' and 'child' data mixed in training/validation/test, which leads to data leakage as test data is being used to generate one new training data.</b>

The correct approach would be to first separate the data and then use SMOTE. Another problem is that <b>SMOTE solves the imbalance issue but does not address the lack of representativeness of input data for each class due to data scarcity</b>. For example, in OBS III, all instances have FCVC = 3.



****************************************************************************************************************************************

### Machine Learning Model for Estimating Student Attrition Risk Percentage

<b>Objective</b>

To develop a toy machine learning model that estimates a student's risk percentage for attrition, assisting educational institutions in taking proactive measures to retain students.

<b>Technologies and Tools</b>

Python, machine learning, classification task

<b>Repository:</b> <a href="https://github.com/leoreigoto/student_evasion">https://github.com/leoreigoto/student_evasion</a>

The repository contains: dataset, code and a technical article.

![image](https://github.com/leoreigoto/leoreigoto.github.io/assets/48571786/c8214f90-ed25-4df0-9576-3e9ba2930a6e)


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


