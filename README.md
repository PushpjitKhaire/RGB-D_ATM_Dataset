# RGB-D_ATM_Dataset
 A unique RGB+D dataset of human actions in ATM, named as (HAD-ATM). For collection of the dataset, Microsoft Kinect v2 sensor is used. Three modalities RGB, depth and skeletal data are captured using this depth sensor. The camera was mounted on top of the ATM to capture the front view of human being. The dataset is collected with five different subjects of distinct heights.  The dataset has total 240 samples of RGB+D data. Duration of each activity varies from 300 frames for a normal activity of transaction to 1400 frames for activity of longer duration.
 
 
Following are the activities collected in ATM environment:
1) transaction without wallet
2) transaction with wallet
3) transaction with bag
4) scratching head/ face while transacting
5) card/ cash fallen while transacting
6) card/cash fallen in the pathway
7) transaction while talking on phone
8) transaction of longer duration
9) Moving around and hitting to the ATM
10) Talking on the phone and moving around.
11) Moving around and searching ( Two person)
12) Moving around and hitting to the ATM (Two person)
13) No transaction and talking to each other (Two Person)
14) Cash stolen from transactor (Two person)
15) Cash stolen from transactor (Three person)
16) Transaction and talking to each other (Two Person)
 
Complete dataset can be downloaded from:

Format of Video File : S1_A1_001.avi  (S: Subject-1,  A: Activity-1,  001: Sample-1)   #Subjects-1:5,  # Activity-1:16, #Samples-1:3

**Depth Data_Link:**

Data_Subject_1:  https://drive.google.com/uc?id=1sjhfOS6Zmi_ZyDy3XlXZJJfB0XBMyMOA&export=download (972 MB)

Data_Subject_2: https://drive.google.com/uc?id=1aaccXyicNQn7fpa3crvujSo5IvSbdXd4&export=download  (1GB)

Data_Subject_3: https://drive.google.com/uc?id=1RHbTY5TksDL-GL5-Z-fmWw-KWi3rUanR&export=download  (1GB)

Data_Subject_4: https://drive.google.com/uc?id=1Surbs5DpiylOrWZmvdXiE3i0H1s_pQRy&export=download  (1.3GB)

Data_Subject_5: https://drive.google.com/uc?id=1vLI_AgHSQHAffHuh1E_JzY3r61TrDaQ8&export=download  (1.1GB)


**Skeleton Data:**

The skeleton data is stored and accessible in (.mat) MATLAB format. The dataset is divided into five
subjects with parent directory “Skeletal_Data” and the sub-directories “S1- S2- S3- S4- S5”.

   - Each subfolder (S1-S5) contains 48 skeleton data samples of the human activities in ATM.
   - Format of (.mat) file in the dataset : S1_A1_001.mat (S: Subject-1, A: Activity-1, 001:Sample-1)

   o #Subjects-1:5
   o # Activity-1:16
   o #Samples-1:3
   
   - For visualization of the skeletal data, a MATLAB code “Show_Structure1.m” is provided with
     the dataset and the implemented, tested, and published code with MATLAB 2021 is given in
     Show_Structure.PDF file 

   - Download_Link: https://drive.google.com/uc?id=1mNgK7VCXKSs8hhEO5uwnupnmNQW-amnF&export=download (44 MB)
