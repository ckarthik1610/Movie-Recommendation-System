# Movie Recommendation System 
This project uses Unsupervised Learning algorithm - "K means clustering" to form clusters of movies according to the average rating given to the movie and the genre the movie belongs to. The Dataset used in this movie recommendation system is from Kaggle's movielens dataset, which contains a large collection of movie data. 

The csv files are first imported in .zip format and then unzipped and processed to form form two pandas data frames namely - "movie" and "rating"

Movie - 

![image](https://github.com/user-attachments/assets/39cd24f0-6c64-4a4d-b684-cc46d4e54e0f)

Rating -

![image](https://github.com/user-attachments/assets/7a92cf94-32cb-41c7-b3d2-c63e42513474)

The final processed data looks like this -

![image](https://github.com/user-attachments/assets/1e80762a-6464-4a78-b97f-0127af826509)

Then the K means clustering model is trained and is used as a system for the recommendation of movies similar to the one you ask for. You input the Movie Id to which the system gives recommendations.
The Output of the system is shown below -

![image](https://github.com/user-attachments/assets/9fcf946d-eac4-4446-b86b-301ed60d6a17)

