# DestinationPredict.
Transforming Travel Experiences

## Project Overview
In the ever-expanding landscape of travel, the aim of this project is to revolutionize the industry by addressing a critical need for personalized recommendations. Traditional travel advisory services fall short in providing tailored experiences, leading to a lack of engagement among modern adventurers. Our project aims to fill this gap by deploying a data-driven solution that enhances user engagement and rejuvenates the travel sector. In order to increase engagement in the travel industry and increase excitement about travel opportunities, this is where DestinationPredict come in handy!

The DestinationPredict is a data product that allows future travelers to get a prediction for their perfect destination with the input of just a few words. Trained on over 28,000 unique text data points, the Destination Dictionary is able to predict a destination from 12 different popular cities with 81% accuracy based on text input of activities you want to do while on vacation.

## Scraping of the Data(Data Mining)
This project utilized data from 12 top cities from TripAdvisor's list of Traveler's Choice destinations for Popular World Destinations , which can be found at (https://www.tripadvisor.com/TravelersChoice-Destinations). The dataset was compiled by scraping the titles from Tripadvisor 'attractions' for each of the 12 cities. The final dataset included over 28,000 unique text values.

# EDA

The Exploratory Data Analysis for this project was mainly devoted to exploring some cleaning and preprocessing techniques for the text data using Natural Language Processing. I also investigated different vectorization strategies for the data and looked into specific words/phrases that needed to be cleaned/removed from the dataset.

## Findings
In order to classify the text data into different classes, I experimented with 3 different vectorization strategies:

-Count Vectorization

-TF-IDF Vectorization

-Count Vectorization using Bi-Grams

After exploring the document term matrices, word clouds, and most frequent words from each of the 3 vectorization techniques, I concluded that the best vectorization strategy is to use TF-IDF vectorization. This strategy is often used to classify news articles into their correct topics, which is a similar use-case to the Destination Dictionary. The purpose here is to classify the text to the correct city, therefore TF-IDF vectorization provides the appropriate ratio to reflect how important a word is to each specific city.
