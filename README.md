# DeepPipes_Dataset

Here we present a dataset which records the scanned point cloud for the pipeline scenario and the labels corresponding to each scanned point cloud.

The dataset consists of a total of 2,000 pipe scenarios, which are evenly distributed across eight folders, that is, 250 scenarios per folder.The first seven folders are the training sets, and the last folder is the validation set.

Each pipeline scenario has a.PTS file in the train_data folder and a .SEG file with the same name in the train_label folder. 

Each line in the. PTS file represents the coordinate of a scanned point. In the.SEG file, each line represents the labels for a corresponding scanned point.
The first three values represent the direction vector of the point,  that's the unit vector from scanned point to axis point.
The fourth value is component type, the fifth value is the radius label，and the last three values are the coordinate of axis point corresponding to the scanned point.

The radius  category label  ranges from 0 to 22. 
The corresponding relationships between 23 classes and diameters are as follows:
0:73, 1:88.9 , 2:114.3, 3:141.3, 4:168.3, 5:219.1, 6:273.0, 7:323.8, 8:377, 9:426, 10:480, 11:530, 12:630, 13:720, 
 14:820, 15:920, 16:210, 17:240, 18:265, 19:320, 20:375, 21:440, 22:490.
The diameters are measured in centimeters.
