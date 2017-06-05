# mavi
Application of Intel RealSense R200 depth perception for pothole detection in MAVI

Sachin Yadav 2011CS50293 IIT Delhi CSE

MTP 1 & 2 dataset

Acknowledgements : Anupam Sobti, Durgesh Chaudhary 


1. XDM folder contains color and depth images of potholes captured using Intel RealSense SDK for Windows which shows whether the depth information in the scene is 'BAD', 'FAIR' or 'GOOD', to ensure that all the documented potholes are well captured , as per the RealSense standards. 

2. Subfolder test_xdms contains images of the same scene captured using stream_recorder and SDK. They appear to be similar for the given scene. It ll be important seeneed to check the rate of good frames as the device is subject to many 'BAD' quality photos while capturing in real time (subject to many internal/external factors) , as per the SDK. 

3. Update : Check out recently released Linux SDK for ZR300 for Ubuntu compatible ways to capture images/video. 

4. Video folder contains vlc captured videos used earlier for MTP 1

5. pcd folder contains sample point clouds converted from the depth images / using realsenseviewer

5. rgb folder contains high resolution RGB images used to test certain RGB only algorithms 
