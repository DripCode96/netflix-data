Netflix Movies & TV Shows - Data Cleaning & Exploratory Data Analysis

This project explores the popular Netflix Titles dataset, performs structured data cleaning, and visualizes meaningful insights using Python.

📂 Dataset

Source: Kaggle – Netflix Movies & TV Shows
Rows: 8807
Columns: 12+ (expanded during processing)

Contains metadata about Movies & TV Shows such as:

Title

Director & Cast

Country

Genre

Duration

Release year

Add date on Netflix

Rating

🛠️ Libraries Used
pandas
numpy
matplotlib
seaborn
wordcloud

🔧 Data Cleaning Steps

✔ Created a working copy of original dataset
✔ Filled missing values in:

Director

Cast

Country

Duration

Rating

✔ Converted date_added to datetime
✔ Extracted:

year_added

month_added

✔ Split duration into:

duration_int (numeric)

duration_type (min/season)

✔ Standardized text columns by stripping whitespace
✔ Removed duplicates
✔ Extracted multiple genres into lists
✔ Removed wrongly stored ratings like '84 min'

📊 Visualizations Created
1️⃣ Movies vs TV Shows Count

Bar chart comparing the volume of Movies vs TV Shows added on Netflix.

2️⃣ Rating Distribution

Which ratings appear most? (TV-MA, TV-14, PG-13, etc.)

3️⃣ Top 10 Content-Producing Countries

Shows which countries contribute the most Netflix content.

4️⃣ Content Added Over Time

Line chart showing how Netflix’s catalog grew by year.

5️⃣ Movies vs Shows Over Years

Stacked comparison of movie vs TV catalog growth.

6️⃣ Top Genres

Extracts the 10 most frequent genres (Documentaries, Dramas, etc.)

7️⃣ Top Directors

Bar chart of most featured directors on Netflix.

🎯 Key Insights

📌 Netflix offers more movies than TV shows overall
📌 United States, India, UK, and Japan dominate content production
📌 Rapid growth in titles occurred post-2015, especially TV shows
📌 Most popular genres include Drama, International TV, Documentaries
📌 Ratings skew toward TV-MA, TV-14, PG-13, meaning content is mostly for teens/adults

🚀 How to Run

Download the dataset

Place CSV in your working directory

Install required libraries

pip install pandas numpy matplotlib seaborn wordcloud


Run the .ipynb notebook or .py script

📁 Future Enhancements

Build dashboards in Power BI/Tableau

Predict show types using ML

Scrape live Netflix metadata

🙌 Credits

Dataset by Kaggle
Analysis & Visualizations by Aryan Srivastava

