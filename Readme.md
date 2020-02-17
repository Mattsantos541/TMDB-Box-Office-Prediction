In this dataset, you are provided with 7398 movies and a variety of metadata obtained from The Movie Database (TMDB). Movies are labeled with id. Data points include cast, crew, plot keywords, budget, posters, release dates, languages, production companies, and countries.

You are predicting the worldwide revenue for 4398 movies in the test file.



This dataset has been collected from TMDB. The movie details, credits and keywords have been collected from the TMDB Open API. This competition uses the TMDB API but is not endorsed or certified by TMDB. Their API also provides access to data on many additional movies, actors and actresses, crew members, and TV shows.


How to evaluate the project

It is your job to predict the international box office revenue for each movie. For each id in the test set, you must predict the value of the revenue variable. 

Submissions are evaluated on Root-Mean-Squared-Logarithmic-Error (RMSE) between the predicted value and the actual revenue. Logs are taken to not overweight blockbuster revenue movies.



Results:


Linear Regression: x= budget, runtime                 RMSE= $92,670,238.24 r=0.53
Linear Regression: x= budget, runtime, popularity     RMSE= $86,600,189.41 r=0.59