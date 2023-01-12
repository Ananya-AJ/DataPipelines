PROJECT OVERVIEW:

I am creating a data pipeline using Airflow. The pipeline will download podcast episodes and automatically transcribe them using speech recognition. I will store results in a SQLite database.

Project Steps

Download the podcast metadata xml and parse
Create a SQLite database to hold podcast metadata
Download the podcast audio files using requests
Transcribe the audio files using vosk

File overview:
podcast_summary.py - the code to create a data pipeline

Local Setup
Installation
install the following locally:
Airflow 2.3+
Python 3.8+
Python packages
pandas
sqlite3
xmltodict
requests
vosk
pydub
Installing Airflow can be tricky - Followed below documentation:[airflow installation](https://airflow.apache.org/docs/apache-airflow/stable/start.html)

Data
I have downloaded the data including a language model for vosk, and podcast episodes from the below link
[data](https://www.marketplace.org/feed/podcast/marketplace/)

