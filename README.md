# DeepPipes_Dataset

The dataset records the scan point cloud for the pipeline scenario and the labels corresponding to each scan point cloud.

The dataset consists of a total of 2,000 pipe scenarios, which are evenly distributed across eight folders, that is, 250 scenarios per folder.The first seven folders are the training sets, and the last folder is the validation set.

Each pipeline scenario has a.PTS file in the train_data folder and a .SEG file with the same name in the train_label folder. 

Each line in the. PTS file represents the coordinate of a scan point. In the.SEG file, each line represents the labels for a corresponding scan point.
The first three values represent the direction vector of the point,  that's opposite vector of normal vector.
The fourth value is component type, the fifth value is the radius label，and the last three values are the coordinate of axis point corresponding to the scanning point.

The radius  category label  ranges from 0 to 22. 
The corresponding relationship between 23 classes and diameters is as follows:
0:73, 1:88.9 , 2:114.3, 3:141.3, 4:168.3, 5:219.1, 6:273.0, 7:323.8, 8:377, 9:426, 10:480, 11:530, 12:630, 13:720, 
 14:820, 15:920, 16:210, 17:240, 18:265, 19:320, 20:375, 21:440, 22:490.
The diameter is measured in centimeters.
