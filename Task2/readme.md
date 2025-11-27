# Task 2 – Data Cleaning

### Data Analytics Internship – Oasis Infobyte

## Objective

The objective of this task is to clean the given YouTube Trending Videos dataset. The goal is to identify missing values, remove duplicates, standardize formats, detect outliers, and prepare the dataset for further analysis.

---

## Dataset Used

**Files:**

* USVideos.csv
* US_category_id.json

The dataset contains information such as:

* video_id
* trending_date
* title
* channel_title
* category_id
* publish_time
* tags
* views
* likes
* dislikes
* comment_count
* description

---

## Tools and Technologies Used

* Python
* Jupyter Notebook / VS Code Notebook
* Pandas
* NumPy

---

## Steps Performed

### 1. Data Loading

* Loaded the CSV and JSON files using pandas and json modules.
* Viewed the first few rows to understand the dataset structure.

### 2. Handling Missing Values

* Checked the entire dataset for missing values.
* Found missing values only in the description column.
* Filled all missing descriptions with "No description".

### 3. Removing Duplicate Records

* Searched for duplicate rows in the dataset.
* Removed all duplicates to ensure clean and accurate data.

### 4. Standardization

* Cleaned and simplified the publish_time column.
* Converted it into a new readable date column called publish_date.

### 5. Outlier Detection

* Identified extreme values in numerical columns:

  * views
  * likes
  * comment_count
* Used the 1%–99% quantile method to detect unusually high or low values.

---

## Project Files

* Task2_Data_Cleaning.ipynb – Notebook containing the full cleaning process
* readme.md – Documentation file
