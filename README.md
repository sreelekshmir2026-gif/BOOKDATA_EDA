# 📚 Exploratory Data Analysis of Books Dataset

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a books dataset containing information about books, authors, ratings, genres, publication dates, publishers, popularity, and other book-related attributes.

The main objective is to identify patterns and relationships related to **book ratings, popularity, authors, genres, publication trends, and reader preferences**.

## 📊 Dataset

- **Rows:** 52,478
- **Columns:** 25
- **Duplicate rows identified:** 50
- **Duplicate rows removed:** 50
- The dataset contains numerical and categorical features.
- The dataset includes information such as:
  - Book title
  - Author
  - Rating
  - Language
  - Genres
  - Number of ratings
  - Liked percentage
  - Publication dates
  - Publisher
  - Price
  - BBE score
  - BBE votes

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Analysis Performed

### Data Understanding

- Displayed the first and last rows
- Checked dataset shape
- Checked column data types
- Generated dataset information
- Generated summary statistics

### Data Cleaning

- Identified missing values
- Checked duplicate records
- Removed duplicate rows
- Examined data types

### Exploratory Analysis

The project explores different aspects of the books dataset, including:

- Most frequently appearing authors
- Most common book languages
- Book ratings
- Number of ratings
- Liked percentage
- Popularity-related measures
- Relationships between numerical variables
- Publication trends
- Other book-related patterns

## 📈 Visualizations

The analysis uses **Matplotlib and Seaborn** to create visualizations and understand relationships between different book attributes.

Examples include:

- Rating distributions
- Rating vs. Number of Ratings
- Rating vs. Liked Percentage
- Author-based analysis
- Other numerical and categorical comparisons

## 💡 Key Insights

The analysis helps understand:

- Which authors appear most frequently in the dataset
- How book ratings are distributed
- How the number of ratings varies across books
- The relationship between ratings and reader-liked percentage
- Patterns in book popularity and other book attributes

## 📁 Project Structure

```text
Book-EDA/
│
├── EDA_Bookdata.ipynb
├── bookdataset.csv
└── README.md
```

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

4. Open the notebook:

```bash
jupyter notebook EDA_Bookdata.ipynb
```

5. Make sure `bookdataset.csv` is placed in the same folder as the notebook.
6. Run the notebook cells to reproduce the analysis.

## 👩‍💻 Project Type

**Exploratory Data Analysis (EDA) Project**

This project demonstrates the use of Python for data cleaning, data exploration, statistical analysis, and visualization.
