1. **Data in the labActivities:** *Squatting down*, *standing up*, walking, *running*, *falling, climbing*. 
2. **Lab_data.csv**: activity samples in the lab. **Data dimension:** 480x54000. Each row is a sample, dimension 200x270, expanded into diemension 1x54000. 480 rows, representing 6 activities, 8 locations, 10 samples per activitity per location.*
3. **Lab_label.csv**: activity labels in the lab. **Data dimension**: 480x6. Each row corresponds to each row in Lab_data.csv, in the form of one-hot encoding.
4. **Data in the lobbyActivities:** *squatting down*, *standing up*, *jumping*.
5. **Lobby_data.csv**: activity samples in the lobby. **Data dimension**: 600x54000. Each row is a sample, dimension 200x270, expanded into diemension 1x54000. 600 rows, representing 3 activities, 20 locations, 10 samples per activity per location.
6. **Lobby_label.csv**: activity labels in the lobby. **Data dimension**: 600x3. Each row corresponds to each row in Lobby_data.csv, in the form of one-hot encoding.
7. Note: 1. The data was collected with IWL5300.
8. Note: 2. The setup had 1 transmitter with 3 antennas, 1 receiver with 3 antennas.
9.  Each antenna pair had 30 groups of subcarriers.3. All the values are CSI amplitude.

