## Netflix Movies and Tv-Series Clustering

Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

![image](https://github.com/sahil-kishor/Netflix-Movies-and-Tv-Series-Clustering/assets/159517524/6801e807-d430-4c45-a39b-7acc54955c68)

## Project Summary: 

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. The project,

1. Exploratory Data Analysis
2. Understanding what type content is available in different countries
3. Clustering similar content by matching text-based features

## Dataset Description:

![image](https://github.com/sahil-kishor/Netflix-Movies-and-Tv-Series-Clustering/assets/159517524/995c4ae1-9953-4745-9a4a-0f4d4bd32711)

## Project Architecture:

![image](https://github.com/sahil-kishor/Netflix-Movies-and-Tv-Series-Clustering/assets/159517524/b0b9b271-59f6-4bda-9829-30f95f1507b8)

## Tasks Performed:

1. Importing Data :- Imported daset into Google Colab notebook and converted in into a Pandas dataframe using Pandas Library
2. Data Cleaning :- Handling null values, duplicate data and outliers present in our data. The column 'director' had 30% of null values followed by 'cast' with 9%, 'coutry' with 6.51%, 'date added' with 0.13% and 'rating' column with 0.09% of null values which were replaced or imputed or dropped as per the requirement. There were no noticeable Duplicate values.
3. Data Wrangling :- Changed the data type of 'date_added' column to datetime format and extracted the year, month and minute values as seperate columns
4. Exploratory Data Analysis :- Plotted the dependent variable and analyzed the distributions of both dependent and independent variables. Checked and visualized the correlation between the dependent and independent variables, and explored the relationships between each pair of variables through various visualization techniques.







