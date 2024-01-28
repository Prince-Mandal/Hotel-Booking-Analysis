# Hotel-Booking-Analysis

Objective

The goal of this project was to analyze hotel review data to gain insights into customer satisfaction across luxury hotels in Europe. Specifically, we aimed to identify hotels with the worst and best reviewer scores to analyze differences.

The dataset contained over 500,000 customer reviews and ratings across 1,493 European luxury hotels. It included details like reviewer nationality, review dates, ratings, text from negative and positive reviews, and hotel location data.

Methodology 
The Python Jupyter notebook loaded the CSV dataset and explored it using Pandas and NumPy to understand the shape, check for missing data, remove unnecessary columns, etc. Data cleaning steps like handling missing values were taken before proceeding with analysis. Matplotlib and Seaborn were used for key visualizations:

- Correlation heatmap to identify relationships between metrics like reviewer score and average score
- Bar plots comparing the bottom 10 and top best hotels by reviewer score

Key Insights
- There was a very high correlation (0.9) between the reviewer score and the average score, indicating consistency.
- The worst hotels had very low (below 5/10) reviewer scores, often coupled with higher negative review word count.
- The best hotel scored a perfect 10/10 reviewer score and had more words in its positive reviews.
- There is a powerful correlation between average ratings and reviewer ratings for hotels.
  
The word count in negative reviews had a moderate negative correlation with ratings. So when issues led to lengthy complaints, reviewer scores dropped. We could predict scores based on negative review lengths alone to a certain degree.

We analyzed both ends of the spectrum - the bottom 10 and the top best-rated properties. Issues like room cleanliness, staff behavior, and value for money commonly appeared as pain points. The highest-rated hotels on the other hand offered services tailored to needs and provided luxury amenities. This analysis highlighted what was separated greatly from poor hospitality.


