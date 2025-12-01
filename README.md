**Amazon Prime Video**
**---> Project Overview**
This project analyzes the Amazon Prime Video Titles Dataset to understand the platform’s content strategy, growth patterns, and audience segmentation.
The focus is on exploring how Prime Video distributes its content across genres, countries, ratings, and release years, and presenting insights through a well-structured Power BI dashboard.
The dataset covers titles ranging from early cinema years to 2021, offering a clear view of how Prime Video’s library has expanded and diversified over time.

**---> Dataset Summary**
Each row represents a single movie or TV show available on the platform.
The dataset includes:
Title – Name of the content
Type – Movie or TV Show
Director & Cast – Key creators
Country – Production origin
Date Added – When it was added to Prime Video
Release Year – Original release year
Rating – Audience maturity rating
Duration – Runtime (movies) or number of seasons
Genres (listed_in) – Category such as Drama, Comedy, Action

**---> Business Objectives**

The analysis aims to answer strategic questions related to:
1. Content Distribution
Volume of titles
Movie vs TV show ratio
Top contributing countries

2. Genre Insights
Most frequent genres
Genre dominance in movies vs TV shows

3. Ratings Analysis
Rating categories with maximum titles
Maturity distribution (Kids, Teens, Adults)

4. Temporal Trends
Content production from 1920–2021
Identifying spikes in growth across decades

5. Geographic Insights
Country-level contribution
Regional genre or rating patterns

**---> Tools & Techniques**
**Power Query (Power BI)**
Removed duplicates and nulls
Standardized columns (dates, ratings, duration)
Extracted numeric values from duration
Cleaned multi-genre fields for analysis

**Power BI Visualizations**
Bar Charts – Ratings, genres, and countries
Donut Chart – Movies vs TV Shows
Line Chart – Titles released across years
Map Visualization – Geographic distribution
Matrix/Table – Title-level exploration

**DAX Measures**
Dynamic counts (movies, TV shows, genres)
Year-based filtering
Ratio calculations

**---> Key Insights**
1. Content Type
Prime Video leans heavily toward movies, indicating a stronger focus on film releases rather than long-form series.

2. Genres
Drama and Comedy dominate the library, forming a significant share of all titles.
Action and Documentary also appear frequently.

3. Ratings
The platform is primarily geared toward teen and adult audiences.
Ratings like 13+, 18+, and TV-MA appear most often.

4. Release Year Trend
Prime Video's library expands dramatically after 2000, with the highest surge between 2015–2021.

5. Country Contribution
The U.S. and India contribute the largest number of titles.
Europe and South Asia also represent major content hubs.

**---> Deliverables**
Cleaned dataset
Power BI dashboard (interactive)
Visual insights for executives
Slicers for type, rating, genre, and country
Time-series exploration for content growth

**---> Future Scope**
Integrate IMDb ratings for quality scoring
Analyze average runtime by genre
Add language-based filtering
Perform cross-platform comparison (Netflix, Hulu, Disney+)
Build predictive insights (content demand forecasting)

**---> Conclusion**
The analysis demonstrates how Amazon Prime Video has evolved into a diverse global platform with a strong emphasis on movies, mature content, and genre versatility.
The dashboard translates these patterns into clear, actionable insights that support strategic decision-making and deeper analytics.
