Netflix Data Analysis

Overview

This project provides an in-depth analysis of Netflix's content dataset, leveraging tools like Power BI, Pandas, and DAX to uncover key insights. The analysis focuses on understanding content distribution, ratings, duration, and geographical trends to provide actionable business intelligence.

Key Features

Data Cleaning:

Handled missing values for director, cast, and country columns.

Extracted duration in minutes from the duration column.

Converted categorical variables to appropriate formats for analysis.

Data Visualization:

Created an interactive dashboard using Power BI.

Visualized data distribution with pie charts, bar graphs, and KPI cards.

Advanced Measures:

Calculated key metrics such as:

Average Rating: Average of all content ratings.

Content Duration in Minutes: Total and average duration of movies and shows.

Content Distribution by Type, Rating, and Country.

KPI Highlights:

Total content count.

Average duration of content.

Distribution of content types (Movies vs. TV Shows).

Tools and Technologies

Power BI:

Designed an interactive dashboard with slicers for filtering by type, rating, and country.

Utilized DAX to create custom measures and KPIs.

Python (Pandas):

Data cleaning and preprocessing.

Exported cleaned data as a CSV for Power BI.

Dashboard Features

Key Visualizations

KPI Cards:

Total Content.

Average Rating.

Average Duration.

Pie Charts:

Content Distribution by Type (Movies vs. TV Shows).

Content Distribution by Rating.

Content Distribution by Country.

Bar Graphs:

Top 10 Countries by Content Count.

Top 10 Directors with Most Content.

Slicers:

Filter by Year Added, Country, and Rating.

How to Use

Prerequisites

Python 3.10 or later.

Power BI Desktop.

Required Python Libraries: pandas, numpy.

Steps

Data Preparation:

Use the provided cleaned_netflix_data.csv file.

Open the dataset in Power BI.

Power BI Report:

Import the data into Power BI.

Use the provided measures and visualizations to build the dashboard.

Customization:

Modify slicers and filters to explore specific insights.

Dataset

Source

Netflix data retrieved from Kaggle and cleaned using Python.

Columns

show_id: Unique identifier for each content.

type: Type of content (Movie or TV Show).

title: Title of the content.

director: Director(s) of the content.

cast: Main cast members.

country: Country of origin.

date_added: Date content was added to Netflix.

release_year: Year content was released.

rating: Audience rating.

duration: Duration in minutes or seasons.

listed_in: Categories or genres.

description: Brief description of the content.

Results and Insights

Netflix has a balanced distribution of Movies and TV Shows.

United States and India are the top contributors to Netflix’s content library.

Content rated TV-MA is the most prevalent on the platform.

The average movie duration is approximately 90 minutes.

Future Enhancements

Add trend analysis for content added over the years.

Analyze viewership data if available.

Explore advanced predictive analytics for rating and content popularity.

Contribution

Contributions are welcome! If you have suggestions for improvement, feel free to submit a pull request or raise an issue.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

Special thanks to Kaggle for the dataset and Netflix for providing inspiration for this analysis.
