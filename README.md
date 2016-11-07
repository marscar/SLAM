##Introduction

The package includes an application that uses the device’s camera (webcam or any attached camera to the computer/laptop) and tracks the movement of a printed image/photograph.  

The software included has been dveloped and tested on a Linux OS (Trusty 14.04)and compiled using cmake. The following instruction are relative to this environment

##Folder structure

|..|build  
|  
|..|data  
|  
|CmakeLists.txt  
|  
|out_camera_data.xml  
|  
|README.txt  
|  
|rtTracker.cpp  

###build 
includes binary file

###data
includes various images used for the experimental setup

**CmakeLists.txt**: compiler settings

**out_camera_data.xml**: camera calibration data

**rtTracker.cpp**: source code

##Installation
- download or clone the repository from [github](https://github.com/marscar/RCPRG_laser_drivers) and place them in the same folder; create a subfolder and name it build.
- on a terminal:  
```
cd <PATH_T0_SOURCE_FILE>/build
camke <PATH_T0_SOURCE_FILE> && make
```

##Execution
- on a terminal:  
```
cd <PATH_T0_SOURCE_FILE>/build
.rtTracker <image_filename>
```

##Media
[slam](https://youtu.be/o6yQOMzt_y8)

##Author
Marcello Scarnecchia
# SLAM
