---
# Welcome to the Github account of the robotics team from the Willibald Gluck Gymnasium Neumarkt (Germany).
--- 
![Logo](https://github.com/wggRobotic/.github/assets/120591442/71076e2b-45c4-4d95-84df-6dd16ad28a9a)

## About us

|  |  |
|-----:|-----------|
|Team name     | WGG Robotics  |
|Name of robots |   N 10  and Idefix  |
|School        | Willibald-Gluck-Gymnasium Neumarkt      |
|Country        | Germany      |
|Instagram | [wgg_Robotik](https://www.instagram.com/wgg_robotik/) |
|email contact     | robotik@wgg-neumarkt.de  |

**Mentors:**

- **Tobias Wagner**: 
He is the team mentor, and he helps with delivering or ordering the needed parts for our robot. He also gives good advice and tips on how to assemble the robot. Additionally, our mentor also gives us directions when needed.

- **Antonello Pastore**:
- **Raffael Pöggel**:

**Members:**
- **Jonas Nicklas**:
He is our main programmer and does most of the software work. He also helps the other team members by explaining and teaching them how to code.

- **Florian Schäff**:
He focuses on making the 3D design of the chassis of our robot. He also helps Lino with building the robot.

- **Dalea Badri**:
Dalea focuses on taking care of the logistics and organizes the TDP. She is also in charge of our social media account.

- **Fiona Schäff**:
Fiona’s emphasis is on the logistics as well and she handles the TDP together with Dalea, too. If help is needed with the hardware, she lends a hand. She overlookes the whole team.

- **Lino Odenbach**:
Lino’s job is to work on the hardware with Florian Schäff and constructing the robot.

- **Christopher Zech**:
Since he is quite talented and interested in math and programming, he focuses on all the informatics and mathematical aspects as well as programming and the software. He works closely together with Jonas.


We work as a team on all our robotic projects. Right now we have four projectes, which are at different states of progression.

![PXL_20250316_104511655](https://github.com/user-attachments/assets/355cd2eb-5ce6-4adf-9505-51f34e6a8cf7)


- [Our Rover - N10](https://github.com/wggRobotic/CAD-Files-N10_version_4_0)
- [Our Robo Dog - Idefix](https://github.com/wggRobotic/CAD-Files-Idefix)
- Our SLAM-Testplattform - noname
- the humanoid Robot Ellie (loaned from the TH Nuremberg)


## Our School

![WGG2](https://github.com/wggRobotic/.github/assets/120591442/5a6a1017-aaa8-4f51-a416-ad4f99746f07)

[Willibald-Gluck-Gymnasium Neumarkt](https://www.wgg-neumarkt.de/)

Woffenbacher Straße 33

92318 Neumarkt 

Bavaria Germany

## Our rover - N10

As a team, we want to be as transparent as possible, so we have decided to make all our components and programmes available as open source. All important information and notes on hardware and software are stored on this Github. Here is a small overview of the links to the most important repositories. These will be updated and supplemented with further information.

Our rover, N10, has participated in the RoboCup World Championship 2024 in Eindhoven in the RMRC league (Rapidly Manufactured Robot Challenge). This was the first real competition for our newly founded team.

The rover was designed and built in under two months, which led to some challenges along the way. Our previous TDM (Team Description Material) and the original design can be found in the following links:

+ [TDM](https://github.com/wggRobotic/N10-Robot)
+ [Hardware - Robot Design and Components](https://github.com/wggRobotic/CAD-Files-and-Components-N10)


The lessons we learned in Eindhoven were incorporated into our new rover design. We developed a completely new modular main body. While the rocker-bogie suspension remains largely the same, the adjustments to the models and a different 3D-printing method have significantly improved the durability of the parts. Additionally, both the robotic arm and gripper feature a new design.

![New_Design](https://github.com/wggRobotic/CAD-Files-N10_version_4_0/blob/main/Rover_Render.png)

All components, a list of the parts etc. can be found here: [N10_v.4.0](https://github.com/wggRobotic/CAD-Files-N10_version_4_0)

Software is here:
+ [Software - GUI](https://github.com/wggRobotic/guiniverse)
+ [Software - Servocontroller](https://github.com/wggRobotic/N10-PCA9685-Servo-Controller)
+ [Software - Motorcontroller](https://github.com/wggRobotic/N10-EduDrive)
+ [Software - Translator](https://github.com/wggRobotic/N10-Translator)
+ [Software - Cam](https://github.com/wggRobotic/N10-CAM-PUB)
+ [Software - Cam-Dif](https://github.com/wggRobotic/N10-CAM-DIF)

![PXL_20250316_104922973](https://github.com/user-attachments/assets/5a1f4b3d-9240-4e39-8d79-b08e455e59ed)

## Our robo dog - Idefix
Together with Antonello and Raffael, the wggRobotics team had long wanted to build a robotic dog. This year, we finally made it happen! 

Our insperiation came from [Spot](https://bostondynamics.com/products/spot/) by Boston Dynamics and the open-source project [SpotMicro](https://spotmicroai.readthedocs.io/en/latest/).  After initial tests during Consumenta 2024 in Nuremberg, we decided to redesign the dog and use different servo motors.

And now, here is our Idefix!
![Render_picture](https://github.com/wggRobotic/CAD-Files-Idefix/blob/main/Render.png)

All components, a list of the parts etc. can be found here: [Hardware](https://github.com/wggRobotic/CAD-Files-Idefix)

Software here:
[RoboDog](https://github.com/wggRobotic/Robodog)



https://github.com/user-attachments/assets/3ce6da89-32ee-4619-8f60-831c08065a4c



## SLAM-Testplattform

Our test robot, "noname," serves as a platform for evaluating various additional modules, including LIDAR, AI cameras, and depth perception sensors. The ultimate goal of this project is to develop an autonomous navigation system capable of real-time environmental mapping and decision-making.

![noname2](https://github.com/user-attachments/assets/4da282e3-69ae-44ec-abcb-da059e96ab5f)

### Core Components

To achieve these objectives, "noname" is equipped with state-of-the-art hardware:

- OAK-1-Lite W Camera – An AI-powered vision system for object detection and recognition.

- Intel RealSense D435 – A depth camera providing precise 3D perception.

- Slamtec RPLIDAR C1 – A high-precision LIDAR sensor for mapping and obstacle detection.

- Siemens IPC127E – A robust industrial PC handling data processing and computational tasks.

### Project Goals

The primary focus of "noname" is to test and integrate these technologies for efficient autonomous navigation. By leveraging sensor fusion and advanced algorithms, the robot will be able to generate accurate maps of its environment and navigate without human intervention.

With further development, "noname" will contribute to research in autonomous robotics and intelligent mobility solutions.

## Some impressions of this year:

https://github.com/user-attachments/assets/12c9b8ec-2941-46bf-9695-673f16e78a47

https://github.com/user-attachments/assets/b2058a91-13ac-4f60-ae79-b801f5b2d1aa

https://github.com/user-attachments/assets/adbed18d-dd04-403e-a9ff-ff6170b28d28

https://github.com/user-attachments/assets/556958c1-1f1c-4b2d-a9cf-4652c63c2d24


https://github.com/user-attachments/assets/2dd72708-536b-4db9-812a-86dcd8f2101b

https://github.com/user-attachments/assets/87338a22-1832-4732-9fc9-d66f5ca65751

https://github.com/user-attachments/assets/c77c3a6f-25b2-4485-90a8-084a5e76c71a



## Some impressions from last year:
**N-10 is alive**

https://github.com/wggRobotic/.github/assets/120591442/5d80d2d2-a150-4501-a7a2-787e2e8cfe9d


https://github.com/wggRobotic/.github/assets/120591442/e944dfcd-308b-43ab-a482-018e04e4b8ce

**The arm is moving**

https://github.com/wggRobotic/.github/assets/120591442/fc6a87b9-1572-44e3-bfca-a64c60b1a6ae









