# 📊 NoSQL Challenge - UK Food Establishments Analysis

## 📝 Project Overview
This project focuses on analyzing food establishments in the UK using MongoDB and Python (PyMongo). The dataset includes hygiene scores, business types, and location data.

## 📂 Files in this Repository
- `NoSQL_setup_starter.ipynb`: Sets up the MongoDB database and modifies the dataset.
- `NoSQL_analysis_starter.ipynb`: Performs exploratory analysis on hygiene scores and business types.
- `establishments.json`: The dataset used for this project.

## 🏆 Key Tasks Completed
1. **Database Setup & Cleanup**
   - Imported dataset into MongoDB (`uk_food` database, `establishments` collection).
   - Added missing restaurant ("Penang Flavours").
   - Removed establishments from Dover.
   - Converted incorrect data types for latitude, longitude, and RatingValue.

2. **Exploratory Analysis**
   - Found all establishments with a hygiene score of 20.
   - Identified businesses in London with a `RatingValue >= 4`.
   - Retrieved the top 5 `RatingValue=5` establishments **closest** to "Penang Flavours".
   - Counted establishments with a hygiene score of **0**, grouped by Local Authority.

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone your-repo-url.git
   cd your-repo-name
Install dependencies:
- pip install pymongo pandas
Run Jupyter Notebook:
- jupyter notebook

Open NoSQL_analysis_starter.ipynb and run the cells.
