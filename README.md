🎬 Movie Data Analytics
A data analysis project that explores insights from a movie dataset using Python. The project involves data cleaning, exploratory data analysis (EDA), and visualization to identify trends in ratings, genres, revenues, and more.

📚 Table of Contents
Overview

Dataset

Technologies Used

Project Structure

How to Run

Key Analysis & Insights

Visualizations

Conclusion

Future Improvements

📌 Overview
This project analyzes a dataset of movies spanning multiple years to answer questions such as:

Which genres are most popular?

How does budget correlate with revenue?

What is the distribution of IMDB ratings?

Do higher-rated movies consistently earn more?

📁 Dataset
The dataset includes information about:

Title, Genre, Year, Rating

Director, Writer, Star

Budget, Gross revenue

IMDB score, Number of votes

Runtime, Country, Company

Source: movies_cleaned.csv (pre-cleaned version of a larger movie dataset)

🛠 Technologies Used
Python 3.x

Pandas – for data manipulation

NumPy – for numerical operations

Matplotlib & Seaborn – for visualization

Jupyter Notebook – for exploratory analysis

🧱 Project Structure
bash
Sao chép
Chỉnh sửa
Movie-Data-Analytics/
├── data/                # Raw and cleaned datasets
├── notebooks/           # Jupyter notebooks for analysis
├── output/              # Generated plots and results
├── PrDataJN.ipynb       # Main notebook
├── README.md            # Project documentation
└── requirements.txt     # List of required libraries
▶️ How to Run
Clone this repository:

bash
Sao chép
Chỉnh sửa
git clone https://github.com/DFrance2934/Movie-Data-Analystics.git
cd Movie-Data-Analystics
Install required dependencies:

bash
Sao chép
Chỉnh sửa
pip install -r requirements.txt
Run the notebook:

bash
Sao chép
Chỉnh sửa
jupyter notebook PrDataJN.ipynb
📈 Key Analysis & Insights
Drama and Action are the most common genres.

Higher-budget films tend to have higher gross revenue but not always higher ratings.

There is a moderate correlation between the number of votes and IMDB score.

Directors like Christopher Nolan and Steven Spielberg frequently produce high-grossing films.

📊 Visualizations
🎯 IMDB Rating Distribution
Visualizes how most films cluster around ratings of 6–8.


💸 Budget vs Gross Revenue
Illustrates the spread of earnings based on investment.

<!-- Placeholder for another plot -->
🧠 Conclusion
This analysis provides valuable insights into what contributes to a movie's success. While budget and genre play significant roles, audience ratings and directorial influence also appear to be important. However, high revenue does not always align with high ratings, indicating that commercial success and critical acclaim are not always correlated.

🚀 Future Improvements
Apply machine learning models to predict gross revenue or rating.

Create an interactive dashboard using Streamlit or Plotly Dash.

Analyze additional datasets (e.g., Rotten Tomatoes, Netflix, etc.)

Add time-series analysis on yearly trends.
