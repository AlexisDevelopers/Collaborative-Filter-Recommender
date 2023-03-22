This project implements a collaborative filter-based recommender system using the Surprise Python library. The data set used contains information about movie ratings by users, and the SVD algorithm is used to generate personalized recommendations for each user.

First, the dataset is loaded and a subset of the movie's features is selected to be used in the project. The Surprise library is then used to create a training dataset and the SVD algorithm is trained using this dataset.

After training the model, a set of recommendations is generated for each user using the get_top_n() function that takes the model's predictions as input and returns the N highest rated movies for each user. These recommendations are stored in a pandas DataFrame and a merge function is used to add additional information about the movies (such as titles) to the recommendations.

Finally, a benchmarking of several different recommendation algorithms is carried out using the Surprise library and it is shown how to generate recommendations for a specific user.