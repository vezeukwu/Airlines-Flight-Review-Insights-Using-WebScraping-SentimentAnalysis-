![image](https://github.com/user-attachments/assets/c102bc3c-67f8-4237-8eef-cfe2b24510f2)


# Airline's Flight Review Insights Using WebScraping-SentimentAnalysis

## Project Overview
This project focuses on extracting and analyzing customer reviews from Skytrax -  a flight review website to derive actionable insights. The primary goal is to utilize web scraping and sentiment analysis techniques to evaluate customers feedback, identify strengths, and address areas of improvement in the aviation industry.

### Tools and Technologies Used:
- **Python**: Programming language for the entire workflow.
- **BeautifulSoup**: For web scraping and extracting textual data.
- **Pandas**: For data cleaning and manipulation.
- **NLTK (Natural Language Toolkit)**: For text preprocessing and sentiment analysis.
- **WordCloud**: For visualizing frequently used words.
- **Matplotlib/Seaborn**: For data visualization.


## Features
1. **Web Scraping**:
   - Extract customer reviews directly from an airline's website.
2. **Data Cleaning**:
   - Removal of HTML tags, special characters, and unnecessary whitespace.
   - Tokenization and lemmatization of text.
3. **Sentiment Analysis**:
   - Categorization of reviews into positive, neutral, or negative sentiments.
   - Calculation of average ratings for each sentiment category.
4. **Word Frequency Analysis**:
   - Identification of most common positive and negative words.
   - Visualization using word clouds.
5. **Actionable Insights**:
   - Recommendations based on customer feedback trends.



## Process

1. **Run the Web Scraper**: I modified the URL in the `web_scraper.py` file to the desired airline review page and ran the webscraper script. This saved the data as a CSV file.
  
2. **Perform Data Cleaning**: I performed data cleaning by removing the html tags, special characters, unnecessary whitespaces, performed tokenization and lemmatization of text
  
3. **Sentiment Analysis**: I then proceeded to categorize reviews into positive, negative and neutral sentiments, and calculated the average ratigs for each category.

4. **Visualize Results**: I further generated word clouds and bar charts to visualize the customers sentiments and ratings.


## Results

### Sentiment Analysis:
- **Positive Sentiment**: 70% of reviews, highlighting exceptional service and comfort.
- **Negative Sentiment**: 20% of reviews, focusing on seating discomfort and limited meal options.
- **Neutral Sentiment**: 10% of reviews.

### Word Frequency Highlights:
- **Top Positive Words**: Service, Comfortable, Business Class, Security.
- **Top Negative Words**: Seats, Vegetarian, Lisbon, Delays.

### Visualizations:
- Sentiment distribution bar chart.
- Word clouds for positive and negative feedback.

## Key Recommendations

1. **Enhance Seating Comfort**: Address feedback regarding economy-class seating.
2. **Improve Dietary Options**: Focus on diversifying vegetarian meal offerings.
3. **Route-Specific Analysis**: Investigate customer dissatisfaction on specific routes (e.g., Lisbon).
4. **Leverage Strengths**: Expand and promote premium services like business class and security enhancements.

