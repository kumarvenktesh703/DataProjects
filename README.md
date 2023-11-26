# This project aims to develop a user-friendly Streamlit application that utilizes the Google API to extract information on a YouTube channel, stores it in a MongoDB database, migrates it to a SQL data warehouse, and enables users to search for channel details and join tables to view data in the Streamlit app

# STEPS TO PROGRESS FOR THE PROJECT:-
------Import all the libraries needed for this project and install them using pip command
      # from googleapiclient.discovery import build,import json,import re,import certifi,import pymongo,import base64importmysql.connector,
        import sqlalchemy,from googleapiclient.errors import HttpError,from sqlalchemy import create_engine,import pymysql,import pandas as         pd,import streamlit as st,import plotly.express as px.
------Creation Of Page Layout,Title declaration and headers along with background image.
------Collection of data from user using youtube API key.
------Definition and Calling of different functions for channel details,videos details,videos ids,time duration of videos and comments           extraction.
------MongoDB connection and storing the data in mongodb database using mongodb connection url.
------Tranfering the data from mongodb database collection to sql database tables using dataframes created using pandas.
------Analysis of the available channel data using the dropdown menu habing different questions
      1.What are the names of all the videos and their corresponding channels?
      2.Which channels have the most number of videos, and how many videos do they have?
      3.What are the top 10 most viewed videos and their respective channels?
      4.How many comments were made on each video, and what are their corresponding video names?
      5.Which videos have the highest number of likes, and what are their corresponding channel names?
      6.What is the total number of likes and dislikes for each video, and what are their corresponding video names?
      7.What is the total number of views for each channel, and what are their corresponding channel names?
      8.What are the names of all the channels that have published videos in the year 2022?
      9.What is the average duration of all videos in each channel, and what are their corresponding channel names?
      10.Which videos have the highest number of comments, and what are their corresponding channel names?
