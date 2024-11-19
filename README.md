# Audio file management with MongoDB

![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

This system is designed to manage .wav audio files using MongoDB. It allows you to store, update, and query metadata associated with audio files, such as recording date, location, duration, and source type. Users can also access tagged audio segments for further analysis. Created as part of a learning project to explore MongoDB database management.

## Features

- **MongoDB database management** to store and organize audio files.
- **Updating URLs** for `.wav` audio files in the database.
- **Querying recordings** by recording date and extracting geospatial data (latitude/longitude).
- **Inserting documents** with detailed information about audio files and segments.

## Project structure

- **create-db**  
   Creates the database and the `files` collection, inserting documents with information about audio files and their segments.

- **add-audio**  
   Updates the URLs of `.wav` audio files in the `files` collection in the database.

- **view-queries**  
   Queries the database for recordings from a specific date and displays geographical coordinates (latitude/longitude).