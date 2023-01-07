# Content-Based-Movie-Recommender-System-with-sentiment-analysis

Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using `beautifulsoup4` and performed sentiment analysis on those reviews.


Don't worry if the movie that you are looking for is not auto-suggested. Just type the movie name and click on "enter". You will be good to go eventhough if you made some typo errors. Also supports uto completion.

## The MovieLens Dataset

One of the most common datasets that is available on the internet for building a Recommender System is the [MovieLens DataSet](https://grouplens.org/datasets/movielens/). This version of the dataset that I'm working with ([1M](https://grouplens.org/datasets/movielens/1m/)) contains 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.Users were selected at random for inclusion. All users selected had rated at least 20 movies. Each user is represented by an id, and no other information is provided.


## Similarity Score : 

   How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
   
   It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.
   

## WebApp Demo

![WebAppImage](https://user-images.githubusercontent.com/55757910/172085677-55846440-0d0d-4cea-b5dc-9e349eb9372d.png)

![WebAppImage1](https://user-images.githubusercontent.com/55757910/172139729-bccdffae-897b-463c-a575-6d95afa3e582.png)

![WebAppImage2](https://user-images.githubusercontent.com/55757910/172139829-7e6efc99-1c5f-4472-9b7a-4494bf77e8b6.png)








