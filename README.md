# WiFi-fingerprint-based-localization-datasets
 
DATASET 1

In this project, we mainly upload a dataset for WiFi fingerprint-based localization, which consists of sequential RSS and IMU data. Therein, the scanning frequencies of RSS and IMU data are 1 Hz and 100 Hz in our datasets, and the detailed contents about our dataset is introduced as follows:

For trainning set, it contains 12 sets of data collected at different times in the target space, and the directories of them is named from final1 to final12. In each directory, there are several RSS data files (with the file name starting with rss) and the corresponding IMU data files (with the file name starting with sen), where the pairwise RSS and IMU files, such as rss1.txt and sen1.txt, are collected on a random crowdsourcing trajectory.

In the RSS data files, there are 24 columns, where the columns from 1 to 22 represent RSS measurements from 22 access points (APs) and the columns from 23 to 24 denote the 2D location labels. In the IMU data files, 9 columns are contained in total, where the columns from 1 to 3 are the 3-axis accelerometer readings, the columns from 4 to 6 are the 3-axis gyroscope readings and the columns from 7 to 9 are the 3-axis magnetometer readings.

For testing set, the data structure is identical with training set.
