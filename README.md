# 🎬 Movie Ratings Analysis and Visualization Dashboard

## 📌 Project Overview

The **Movie Ratings Analysis and Visualization Dashboard** is a data analytics project that explores user movie ratings from the MovieLens dataset. The project focuses on cleaning and preprocessing the data, performing statistical analysis, visualizing rating patterns, identifying top-rated movies and genres, and creating an interactive dashboard to present key findings.

This project demonstrates essential data analysis and visualization techniques using Python and popular data science libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Plotly.

---

## 🎯 Objectives

The primary objectives of this project are to:

* Load and explore movie ratings data
* Clean and preprocess the dataset
* Calculate summary statistics of movie ratings
* Visualize the distribution of ratings
* Identify the highest-rated movies
* Analyze ratings across different genres
* Create an interactive dashboard to communicate insights effectively

---

## 🗂️ Dataset Information

This project uses the **MovieLens Latest Small Dataset**, provided by GroupLens Research.

The dataset contains movie information and user ratings collected over several years.

### Files Used

| File Name     | Description                          |
| ------------- | ------------------------------------ |
| `movies.csv`  | Contains movie titles and genres     |
| `ratings.csv` | Contains user ratings and timestamps |

### Dataset Features

#### `movies.csv`

| Column    | Description                      |   |
| --------- | -------------------------------- | - |
| `movieId` | Unique identifier for each movie |   |
| `title`   | Movie title with release year    |   |
| `genres`  | Movie genres separated by `      | ` |

#### `ratings.csv`

| Column      | Description                       |
| ----------- | --------------------------------- |
| `userId`    | Unique identifier for each user   |
| `movieId`   | Unique identifier for each movie  |
| `rating`    | User rating (0.5 to 5.0)          |
| `timestamp` | Time when the rating was provided |

---

## 🔗 Dataset Download

Download the MovieLens Latest Small Dataset from the official website:

https://grouplens.org/datasets/movielens/latest/

After downloading:

1. Extract the ZIP file.
2. Copy `movies.csv` and `ratings.csv` into the `data/` folder.

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly

---
---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/movie-ratings-analysis-dashboard.git
```

Move to the project directory:

```bash
cd movie-ratings-analysis-dashboard
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/movie_ratings_analysis.ipynb
```

---

## 📦 Requirements

Create a `requirements.txt` file with the following dependencies:

```text
pandas
numpy
matplotlib
seaborn
plotly
jupyter
```

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 🔄 Data Preprocessing Steps

The following preprocessing steps are performed:

* Loaded the datasets using Pandas
* Explored the dataset structure and dimensions
* Checked for missing values
* Removed duplicate records
* Converted timestamps into datetime format
* Extracted release years from movie titles
* Merged movie and ratings datasets
* Filtered invalid or missing ratings

---

## 📊 Exploratory Data Analysis

The project performs an in-depth analysis of movie ratings.

### Summary Statistics

The following statistical measures are calculated:

* Mean rating
* Median rating
* Mode rating

These metrics help understand the overall distribution of user ratings.

---

## 📈 Data Visualizations

### 1. Ratings Distribution Histogram

A histogram with a kernel density estimate (KDE) is used to visualize the distribution of movie ratings.

**Insights:**

* Understand the frequency of ratings
* Identify common rating values
* Detect skewness in the data

---

### 2. Ratings Box Plot

A box plot is used to identify:

* Median rating
* Interquartile range (IQR)
* Potential outliers

---

### 3. Top-Rated Movies

Movies are ranked according to their average rating.

To ensure fairness and reduce bias, only movies with a minimum number of ratings are considered.

---

### 4. Genre Analysis

Movies often belong to multiple genres. The project separates genres and analyzes average ratings across each genre.

This analysis helps identify:

* Highest-rated genres
* Most popular genres
* Genre-specific rating trends

---

## 📋 Key Findings

* User ratings are concentrated around higher values.
* Certain genres consistently receive better ratings.
* Popular movies with a large number of ratings provide more reliable insights.
* Filtering movies by minimum rating count improves result quality.

---

## 📊 Interactive Dashboard

An interactive dashboard is created using Plotly.

### Dashboard Features

* Interactive bar charts
* Hover information
* Dynamic exploration of top-rated movies

The dashboard is exported as:

```text
dashboard/movie_dashboard.html
```

Open this file in any web browser to explore the results interactively.

---

## 📤 Output Files

The project generates the following outputs:

| File                    | Description                    |
| ----------------------- | ------------------------------ |
| `ratings_histogram.png` | Distribution of movie ratings  |
| `ratings_boxplot.png`   | Box plot of ratings            |
| `top_movies.png`        | Top-rated movies visualization |
| `top_genres.png`        | Top-rated genres visualization |
| `movie_dashboard.html`  | Interactive dashboard          |

---

## 🚀 Future Enhancements

Potential improvements for this project include:

* Sentiment analysis of movie reviews
* Recommendation system implementation
* Time-series analysis of rating trends
* User segmentation based on preferences
* Advanced dashboards using Tableau or Power BI
* Predictive modeling for rating estimation

---

## 💡 Skills Demonstrated

This project highlights the following skills:

* Data Cleaning
* Data Wrangling
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Dashboard Development
* Python Programming

---

## 📚 Learning Outcomes

By completing this project, you will gain experience in:

* Working with real-world datasets
* Handling missing values and duplicates
* Applying statistical methods
* Creating effective visualizations
* Communicating insights through dashboards

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

Feel free to fork this repository, submit issues, or create pull requests.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Raviraj Totare**

* GitHub: https://github.com/ravirajtotare
* LinkedIn: https://www.linkedin.com/in/raviraj-totare-6a6b03325

If you found this project helpful, consider giving it a ⭐ on GitHub.
