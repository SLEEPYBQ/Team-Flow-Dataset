## Dataset
The dataset is about 34.4 GB including multi-EEG signals data of team flow from 63 pairs of participants.

Although 63 pairs of participants participated in the EEG data acquisition, only 47 pairs of them were included in the final dataset after excluding groups with data acquisition errors and operational failures.

<div align=center>
<img src="./img/Data-Acquisition.png" width=100% >
<br>Fig1 Data Acquisition</div>
The EEG recording devices adopted in this study are two sets of Emotiv Epoc+, which supports the acquisition of up to 14 channels of EEG signals at a sampling rate of 256 Hz.
<div align=center>
<img src="./img/Emotiv.png" width=60% >
<br>Fig2 Emotive Epoc+</div>


All data were saved as CSV files, each of which was a matrix of dimensions [14, 1536]. It represents 14-channel EEG data with 1536 sample points, the sampling rate of the EEG signals is 256 Hz,i.e. each CSV file has a duration of 6 seconds.

During the game, the EEG signals collected from each pair of participants were organized by "group number-participant number-game set number". Each participant's folder contains EEG data sliced from five rounds of game. 

If you need team flow data set, please send an email to 202100800161@mail.sdu.edu.cn