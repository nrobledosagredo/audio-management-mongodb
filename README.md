# Audio file management with MongoDB

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

## Overview

This system manages `.wav` audio files using MongoDB, enabling users to store, update, and query metadata such as recording date, location, duration, and source type. It also supports accessing tagged audio segments for analysis. Developed as a learning project to explore MongoDB database management and Python integration.

## Features

- **Audio metadata storage:** Stores detailed information about `.wav` files, including recording date, location, and duration.  
- **URL management:** Updates and manages URLs for audio files in the database.  
- **Geospatial queries:** Retrieves recordings by date and extracts latitude/longitude data.  
- **Tagged segments:** Organizes and accesses tagged segments within audio files.  
- **Document insertion:** Adds structured documents with audio file and segment details.  

## Setup

1. **Clone the repository**:  
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Set up MongoDB**: Ensure MongoDB is installed and running locally or provide a connection string for a remote instance.

3. **Run the scripts**:  
   - **Create database**:  
     ```bash
     python create-db.py
     ```
   - **Add audio files**:  
     ```bash
     python add-audio.py
     ```
   - **Query recordings**:  
     ```bash
     python view-queries.py
     ```

4. Use the scripts to manage and query audio file metadata and segments.
