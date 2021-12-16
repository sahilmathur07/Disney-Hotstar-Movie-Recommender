# Disney-Hotstar-Movie-Recommender

# Libraries Used
1. Pandas
2. Scikit-Learn
3. Nltk

A. I used Pandas for importing and manipulating data

B. I used Scikit-Learn for vectorizing the text data and finding similarities in the movies

C. I used Nltk for the text data preprocessing

# Steps of creating recommender system

1. Firstly we need to import data
2. Then we need to select relevant colomns to create recommender system
3. Then we need to preproccess the selected columns(like lower case, stopwords removal and etc.)
4. Then we combine the columns (like in my case i combined director, cast, release_year, rating, duration, listed_in, description columns and created a new column named tags)
5. And finally we calculate similarity between the movies
