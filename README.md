# UK Food Establishments Analysis

## Description

This project focuses on analyzing food establishments across the United Kingdom using MongoDB and Python. The goal is to import, clean, and query the data to answer questions about hygiene scores, local authority areas, and geolocation. Technologies used include:

- **Python 3** (for data manipulation and queries)  
- **MongoDB** (for data storage and aggregation)  
- **Jupyter Notebook** (for interactive analysis)

Key challenges addressed in the project include:

- Converting string fields (like latitude/longitude) to numeric types.  
- Aggregating data by local authorities and hygiene scores.  
- Handling geospatial queries to find nearby establishments.

## Table of Contents

- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Credits](#credits)

## Installation Instructions

1. **Install MongoDB**  
   Ensure you have MongoDB installed and running locally (or on a remote server).

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/uk-food-establishments.git

3.**Create and Activate a Virtual Environment**
   ```bash
conda create --name dev python=3.9
conda activate dev


   ```bash
pip install pymongo pandas jupyter


   ```bash
mongoimport --type json -d uk_food -c establishments --jsonArray ./resources/establishments.json




