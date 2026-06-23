# Social Network Data Analysis using Pure Python

## Project Overview

This project performs social network data analysis using **Pure Python** without relying on external data analysis libraries such as Pandas or NumPy.

The project is divided into two folders:

### 1. Main Folder

Contains the original dataset, data cleaning process, and data loading operations.

### 2. project_2 Folder

1.Who has the maximum posts
2.who has the maximum followers
3.Who follows the maximum people
4.How many categories (Digital creators, Non-profit foundation, etc do we have? How many people do we have?
---

## Objectives

The main goals of this project are:

1. Load social network data from JSON files.
2. Clean the dataset.
3. Remove duplicate records.
4. Analyze user connections and page preferences.
5. Generate friend recommendations.
6. Generate page recommendations.
7. Extract useful social network statistics.

---

## Features Implemented

### Data Loading

* Reads user data from JSON files.
* Parses and stores user information using Python data structures.

### Data Cleaning

* Removes duplicate records.
* Handles inconsistent data.
* Creates a cleaned dataset for further analysis.

### People You May Know

Suggests potential friends based on:

* Mutual friends
* Existing social connections

### Pages You Might Like

Suggests pages based on:

* Common interests
* Liked pages of friends

---

## Project Structure

```text
coders-of-india/
│
├── data.json
├── cleaned_data.json
├── clean_data.ipynb
├── liked_pages.ipynb
├── parsing.ipynb
│
└── project_2/
    ├── data.json
    ├── finaldata.txt
    ├── last_final.txt
    ├── parsing.ipynb
    └── recommendation modules
```

---

## Analysis Performed

### 1. User with Maximum Posts

Identifies the user who has created the highest number of posts.

### 2. User with Maximum Followers

Finds the user with the largest follower count.

### 3. User Following Maximum People

Identifies the user who follows the highest number of people.

### 4. Category Analysis

Calculates:

* Total number of categories
* Number of users in each category

Example Categories:

* Digital Creator
* Non-Profit Foundation
* Public Figure
* Business
* Education
* Entertainment

### 5. Total People Count

Calculates the total number of users available in the dataset.

---

## Technologies Used

* Python
* JSON
* Jupyter Notebook

No external data analysis libraries were used. All operations were implemented using core Python concepts such as:

* Lists
* Dictionaries
* Loops
* Functions
* Sorting
* File Handling

---

## Output Examples

* Cleaned Dataset
* Friend Recommendations
* Page Recommendations
* Maximum Posts Analysis
* Maximum Followers Analysis
* Maximum Following Analysis
* Category Statistics
* User Count Statistics

---

## Conclusion

This project demonstrates how social network data can be processed, cleaned, analyzed, and used for recommendation systems using only Pure Python. It provides insights into user behavior, social connections, and content preferences while showcasing fundamental data processing techniques.
