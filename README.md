# Device-free_RF_Human_Sensing_Datasets

This repository contains the dataset that was collected and processed with the objective of counting the number of people in a room using device-free WiFi Channel State Information (CSI) measurement and processing.

WiFi CSI data are extracted from the received packets by using a modiﬁed version of a open-source wireless driver for the Intel IWL-5300 WiFi card. We carried out WiFi CSI collection on three diﬀerent rooms, see uploaded Figure.

CSI measurements have been collected for each class of people (from 0 to 7) and for each room.

The collected CSI data can be processed for feature extraction, feature selection and classiﬁcation tasks.

This dataset may be used for non-commercial research provided you acknowledge the source of the data by citing the following papers:

[1] Simone Di Domenico, Giovanni Pecoraro, Ernestina Cianca, Mauro De Sanctis, "Trained-Once Device-Free Crowd Counting and Occupancy Estimation Using WiFi: A Doppler Spectrum Based Approach", The 12th IEEE International Conference on Wireless and Mobile Computing, Networking and Communications (WiMob 2016), New York (NY), 17-19 October 2016, DOI: 10.1109/WiMOB.2016.7763227

[2] Simone Di Domenico, Mauro De Sanctis, Ernestina Cianca, Giuseppe Bianchi, "A Trained-once Crowd Counting Method Using Differential WiFi Channel State Information", Proceedings of the 3rd International on Workshop on Physical Analytics (WPA’16) co-located with Mobisys 2016, pp. 37-42, Singapore, June 26, 2016, DOI: 10.1145/2935651.2935657

----------------

@INPROCEEDINGS{Di-Domenico-2016-WIMOB, 
author={Di Domenico, Simone and Pecoraro, Giovanni and Cianca, Ernestina and De Sanctis, Mauro}, 
booktitle={2016 IEEE 12th International Conference on Wireless and Mobile Computing, Networking and Communications (WiMob)}, 
title={Trained-once device-free crowd counting and occupancy estimation using WiFi: A Doppler spectrum based approach}, 
year={2016}, 
volume={}, 
number={}, 
pages={1-8}, 
keywords={radio receivers;wireless LAN;trained-once device-free crowd counting;occupancy estimation;WiFi;Doppler spectrum based approach;Doppler effect;IEEE 802.11 Standard;Receivers;Estimation;Radio frequency;Wireless communication;Training;Device-free;People Counting;WiFi;RF sensing;Crowd Counting;CSI;RSSI}, 
doi={10.1109/WiMOB.2016.7763227},
month={Oct},}

@inproceedings{Di-Domenico-2016-WPA,
 author = {Di Domenico, Simone and De Sanctis, Mauro and Cianca, Ernestina and Bianchi, Giuseppe},
 title = {A Trained-once Crowd Counting Method Using Differential WiFi Channel State Information},
 booktitle = {Proceedings of the 3rd International on Workshop on Physical Analytics},
 series = {WPA '16},
 year = {2016},
 isbn = {978-1-4503-4328-2},
 location = {Singapore, Singapore},
 pages = {37--42},
 numpages = {6},
 url = {http://doi.acm.org/10.1145/2935651.2935657},
 doi = {10.1145/2935651.2935657},
 acmid = {2935657},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {crowd counting, csi, device-free, people counting, rf sensing, rssi, wifi},
} 




