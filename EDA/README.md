# Grabbing Data

Data is too big to be stored onto github so download it from the Kaggle


Netflix Dataset: https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data


LastFm: http://ocelma.net/MusicRecommendationDataset/index.html


MovieLens: Can be downloaded from suprise library (note numpy and pandas version will have to be <2.0)


moved the downloaded files into /EDA directory

Parsed Raw Data
https://drive.google.com/file/d/1I3r5O2RY5ggfgz4dk2oJ3MMj2aCIllTC/view?usp=sharing

# Data files

data.txt = combined data

items.txt = itemID (all items in the dataset)

user.txt = userID (trimmed for only users with 100 ratings)

userAll.txt = userID (all users in the dataset)

dataTrimmed.txt = (data.txt with users who have at least 100 ratings)

userTime.csv = user x time matrix (cell value = user_i rated on date_j)

userItem.csv = user x item matrix (cell value = user_i rating of item_j)
