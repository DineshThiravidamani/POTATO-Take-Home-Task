# POTATO Take-Home Task

## Overview
This project is designed to query Twitter data based on user-specified terms. It ingests data, allows term-based queries, and provides insights such as the number of tweets, unique users, average likes, and more. The project was developed as part of a take-home assignment for POTATO, utilizing Python.

## How to Use the System    

### 1. Setup
- You can run the system using **Google Colab**. Simply upload the provided Python script and dataset files.
- Ensure that the dataset file is in `.tsv` format, which will be loaded into the script.

### 2. Query the Data
- The system allows you to query Twitter data for specific terms.
- Example query: Using the term **`Doctor`** will filter tweets containing this word and return results, including the number of tweets, unique users, average likes, and more.

### 3. Key Functionalities
- **Search for a term**: Returns the number of tweets containing the term on each day.
- **Unique users**: Counts the number of unique users who tweeted the term.
- **Average likes**: Calculates the average likes for tweets containing the term.
- **Location-based**: Displays the place IDs where the tweets originated.
- **Time of day**: Shows the times when tweets were posted.
- **Top user**: Identifies the user who posted the most tweets containing the term.

## Design Choices
- The system utilizes **Pandas** for efficient data manipulation and querying.
- The use of `.tsv` format allows for easy handling of large datasets.
- **Google Colab** is chosen for its cloud-based environment, facilitating seamless execution of the code.

## Dependencies
- Python
- Pandas
- NumPy

## Instructions for Running the Code
1. Open Google Colab and create a new notebook.
2. Upload the dataset and the Python script.
3. Run the cells in the notebook to ingest the data and perform queries.

## Conclusion
This project demonstrates the ability to efficiently query and analyze Twitter data using Python, providing valuable insights based on user-defined search terms.

