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

2. Data Cleaning :- Handling null values, duplicate data and changed column datatypes. The column 'director' had 30% of null values followed by 'cast' with 9%, 'coutry' with 6.51%, 'date added' with 0.13% and 'rating' column with 0.09% of null values which were replaced or imputed or dropped as per the requirement. There were no noticeable Duplicate values.

3. Data Wrangling :- Changed the data type of 'date_added' column to datetime format and extracted the year, month and minute values as seperate columns

4. Exploratory Data Analysis :- Plotted the dependent variable and analyzed the distributions of both dependent and independent variables. Checked and visualized the correlation between the dependent and independent variables, and explored the relationships between each pair of variables through various visualization techniques.

6. Feature Engineering and Data Preprocessing:- Handled outliers in the data with Interquartile Range (IQR) method; Categorical Encoding using One Hot Encoding; Textual Data Preprocessing with lowercasing, removing punctuations and stopwords, lemmatization, tokenization and more. Followed by Dimesionality Reduction using PCA.

7. ML Model Implementation :- Found the optimal number of clusters using the Elbow method and Silhouette Score for K-Means Clustering, created 6 clusters according to Silhouette Score. Crafted a dendogram for Hierarchical Clustering and formed 11 clusters and created Word cloud for every cluster formed by K-Means and Hierarchical Clustering

8. Recommender System : Built a Recommender System to recommend relevant items for users, based on their preference

## Insights:
Insights derived from the Exploratory Data Analysis include:

1. Almost 70% of datapoints belong to Movie, rest 30% to TV Show, i.e, Netflix has higher number of Movies than Series

2. TV-MA (Rating suitable only for Matured Audience), has the highest number of Movies and Series compared to other ratings

3. Countries like Mexico, Spain, France, and the United Kingdom predominantly produce content aimed at adults. In contrast, India primarily targets teens with its content. Additionally, content targeting children constitutes only 1% to 27% of the total output across all countries.

4. Analyzing the overall content on Netflix, the most prevalent genres are International Movies, Dramas, and Comedies. In contrast, the least represented genres include Classic & Cult TV, TV Thrillers, Stand-Up Comedy, and Talk Shows.

5. Analyzing movies and TV shows individually, the most preferred movie genres are Documentary, Comedy, Drama and International Movies. For TV series, the highly preferred genres are Kids' TV, International TV Shows, Drama, and Crime.

6. USA holds the largest content share on Netflix, contributing 61% of the total content. This is followed by India, which accounts for 18%, and the UK, which contributes 8% of the content.

## Conclusion
1. Embarking on a Cinematic Adventure with Netflix Data! Launching into Data Realms: Prepare for an exhilarating voyage as we unveil the secrets of Netflix's vast content library through the lens of data science.

2. Data Transformation Magic: Just like wizards, we worked our magic to transform jumbled descriptions into neat and organized data. Imagine tidying up your room, but with words instead of toys!

3. Unlocking the Puzzle of Similarity: Think of movies and TV shows as puzzle pieces, and we sorted them based on their unique shapes and colors. This helped us uncover fascinating connections between seemingly unrelated content.

4. Discovering Hidden Patterns: Imagine being a detective, hunting for hidden clues. We used complex algorithms to discover hidden patterns in the data. It's like decoding a secret message that only data can reveal.

5. Venturing into Clusters of Content: We embarked on a cosmic journey, exploring clusters of movies and shows that share striking similarities. It's like discovering galaxies of content with their own themes and vibes.

6. Crafting Word Art with Clouds: Ever wanted to paint with words? Enter the enchanting world of word clouds, where themes and emotions take shape through the art of language.

7. Sharing the Enchantment: The magic doesn't stop here! We've harnessed the power of data to create personalized Netflix recommendations, tailored just for you.

9. A Spectacular Finale: As the curtains close on our data-driven adventure, remember that the stories continue to unfold. Armed with insights, you're now poised to experience Netflix in a whole new dimension. Lights, camera, data!


## Author

Sahil Kishor
Email : kishorsahil555@gmail.com
LinkedIn : www.linkedin.com/in/sahil-kishor
