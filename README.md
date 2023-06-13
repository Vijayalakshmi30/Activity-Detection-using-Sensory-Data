# Activity-Detection-using-Sensory-Data
Welcome to the exciting project! Our dataset contains sensory data for 10 dedicated volunteers, with each subject contributing to a comprehensive dataset comprising over 100,000 rows and 24 columns. The main objective is to classify 12 different activities, along with a null activity. We have extensively explored various classification algorithms and are thrilled to share that the Random Forest Model and Multilayer Perceptron model have emerged as the top performers. 

### Additional information
The dataset consists of body motion and vital signs recordings from ten volunteers while performing 12 physical activities. Shimmer2 wearable sensors were used, placed on the chest, right wrist, and left ankle, capturing acceleration, rate of turn, and magnetic field orientation to capture body dynamics. The chest sensor also recorded 2-lead ECG measurements for future analysis. All modalities were recorded at a 50 Hz sampling rate. The dataset exhibits generalizability to daily activities, considering the diversity of body parts, intensity, and execution speed. The activities were performed in an unconstrained out-of-lab environment, with participants aiming to execute them to the best of their ability.

### Attribute Informatiom
Each subject's data is stored in separate log files named 'mHealth_subject<SUBJECT_ID>.log'. Each file contains rows representing samples and columns representing sensor recordings. The activity labels in the dataset follow a similar format (e.g., '4' represents walking). 

Here's a breakdown of the meaning of each column:

Column 1: acceleration from the chest sensor (X axis)

Column 2: acceleration from the chest sensor (Y axis)

Column 3: acceleration from the chest sensor (Z axis)

Column 4: electrocardiogram signal (lead 1) 

Column 5: electrocardiogram signal (lead 2)

Column 6: acceleration from the left-ankle sensor (X axis)

Column 7: acceleration from the left-ankle sensor (Y axis)

Column 8: acceleration from the left-ankle sensor (Z axis)

Column 9: gyro from the left-ankle sensor (X axis)

Column 10: gyro from the left-ankle sensor (Y axis)

Column 11: gyro from the left-ankle sensor (Z axis)

Column 13: magnetometer from the left-ankle sensor (X axis)

Column 13: magnetometer from the left-ankle sensor (Y axis)

Column 14: magnetometer from the left-ankle sensor (Z axis)

Column 15: acceleration from the right-lower-arm sensor (X axis)

Column 16: acceleration from the right-lower-arm sensor (Y axis)

Column 17: acceleration from the right-lower-arm sensor (Z axis)

Column 18: gyro from the right-lower-arm sensor (X axis)

Column 19: gyro from the right-lower-arm sensor (Y axis)

Column 20: gyro from the right-lower-arm sensor (Z axis)

Column 21: magnetometer from the right-lower-arm sensor (X axis)

Column 22: magnetometer from the right-lower-arm sensor (Y axis)

Column 23: magnetometer from the right-lower-arm sensor (Z axis)

Column 24: Label (0 for the null class)

*Units: Acceleration (m/s^2), gyroscope (deg/s), magnetic field (local), ecg (mV)

### Citation
Banos,Oresti, Garcia,Rafael, and Saez,Alejandro. (2014). MHEALTH Dataset. UCI Machine Learning Repository.
