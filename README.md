# UCI_341_Dataset
Smartphone-Based Recognition of Human Activities and Postural Transitions

The details of the dataset can be found at https://archive.ics.uci.edu/dataset/341/smartphone+based+recognition+of+human+activities+and+postural+transitions.

The dataset is divided into two parts: raw inertial sensor (accelerometer and gyroscope) data and features extracted from the raw data. All raw data files can be found in RawData folder.

1. The accelerometer data is prefix with 'acc_' and gyroscrope data is prefix with 'gyro_'. 
2. The annotation file is given in 'labels.txt'
3. The activity label is given in 'activity_labels.txt'

The following is the activity labels, which can be found in 'activity_labels.txt'.

1. WALKING           
2. WALKING_UPSTAIRS  
3. WALKING_DOWNSTAIRS
4. SITTING           
5. STANDING          
6. LAYING            
7. STAND_TO_SIT      
8. SIT_TO_STAND      
9. SIT_TO_LIE        
10. LIE_TO_SIT        
11. STAND_TO_LIE      
12. LIE_TO_STAND      

This script combines the individual acc data and gyro data, and label each row with its correponding activity class based on 'labels.txt'. Notice that some rows are not annotated in 'labels.txt'. Thus, the rows are labeled with -1.

Folder UCI_00341 contains the original raw data.

Folder Annotated_Data contains the processed (labeled) data.
