# EU Music Analysis

## Instructions for Adding the Dataset

1. **Download the Dataset:**
   - Access the dataset from this link: [Top Spotify Songs in 73 Countries (Daily Updated)](https://www.kaggle.com/datasets/asaniczka/top-spotify-songs-in-73-countries-daily-updated/data)

2. **Extract the Zip File:**
   - After downloading, extract the zip file.

3. **Copy the CSV File:**
   - Locate and copy the file named `universal_top_spotify_songs.csv`.

4. **Place the CSV File:**
   - Paste the `universal_top_spotify_songs.csv` file into the `dataset` folder of our application.

**Note:** The dataset is large and cannot be uploaded to GitHub.

## Create virtual environment with venv
``` shell
python -m venv venv
```

## Activate the virtual environment
``` shell
venv\Scripts\activate
```

## Install requirements
For local testing ensure that you created a venv virtual environment. Activate this environment and run the following commands.
Install python requirements:

``` shell
pip install -r requirements.txt
```

## Run the Python script
``` shell
python app.py
```
Open your web browser and navigate to http://127.0.0.1:5500. Input the necessary data to interact with the application.