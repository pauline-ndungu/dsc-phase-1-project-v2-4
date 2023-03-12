## Movie Industry: Exploratory Data Analysis
![My Image](Images/Background%20image.jpg)
## Project Description
This project involves  analyzing box office data in an attempt to understand what types of movies are currently popular and successful. This information can be used to make informed decisions about the types of movies to produce and establish themselves as successful players in the movie industry. The first portion involves importing and cleaning the data, and although not all tables will be used, I preliminarily decided to go through and clean all of them. Once the data is cleaned, there are a few questions that I gleaned from the data followed by my recommendations.

## The Data
The data used for this project was pulled from the sources listed below:
* Box Office Mojo: https://www.boxofficemojo.com
* IMDB: https://www.imdb.com/interfaces/
* Rotten Tomatoes: https://www.rottentomatoes.com
* The Movie Database: https://www.themoviedb.org/?language=en-US
* The Numbers: https://www.the-numbers.com/   

The data sources used for this project  provide information on movies:

* Box Office Mojo: Box Office Mojo is a website that tracks box office revenue for movies released in theaters. The website provides information on box office earnings, release dates, budget, and other related information.

* IMDb: IMDb is a popular online database of information related to films, television programs, and video games. The website contains information on movies, including cast and crew, plot summaries, reviews, ratings, and other related information.

* Rotten Tomatoes: Rotten Tomatoes is a website that aggregates movie reviews and provides an overall score for each movie based on the percentage of positive reviews from critics. The website also provides audience scores and user reviews.

* The Movie Database: The Movie Database (TMDb) is a community-built movie and TV database. The website provides information on movies, including cast and crew, plot summaries, reviews, ratings, and other related information. TMDb also allows users to contribute to the database by adding information on movies and TV shows.

* The Numbers: The Numbers is a website that provides box office and financial information for movies. The website provides information on box office earnings, budgets, and other financial information related to movies.

The dataset is relevant in finding out what types of films to create, as it provides a wealth of information on past movies, including box office earnings, audience and critic ratings, and genre classifications. By analyzing the data, filmmakers can identify trends in the types of movies that have been successful in the past, and use this information to inform decisions on future movie productions.

Some of the specific properties of this data may include:

* Movie titles: The names of the movies that are included in the dataset.
* Release dates: The dates when the movies were released in theaters or made available to the public.
* Box office earnings: The amount of money that each movie earned at the box office.
* Budgets: The amount of money that was spent to produce each movie.
* Ratings: The ratings that each movie received from audiences and critics.
* Reviews: Written reviews or comments that audiences and critics provided about each movie.
* Genres: The different categories or types of movies, such as action, comedy, drama, or horror.
* Cast and crew: The actors, directors, and other professionals who worked on each movie.
* Production companies: The companies or studios that produced or financed each movie.


## Objectives
Perform Exploratory Data Analysis techniques on  the data to determine which factors contribute to what types of movies are currently popular and successful at the Box Office.

## Tools
In order to analyze data better and manipulate it, I used the following  libraries:​
Pandas​
Matplotlib​
Seaborn​

## Data Mining
The first step is to collect the necessary data from the selected data sources. In this project, the data sources include preloaded datasets and an IMDb SQL database.

   a. Preloaded datasets: The preloaded datasets are stored in CSV format and can be read into the project using the pandas library in Python.

   b. IMDb SQL database: The IMDb SQL database contains a large amount of movie-related data, such as cast and crew information, plot summaries, and ratings. To access this data, SQL queries can be executed on the database using Python libraries such as pandas. Once the data is queried, it can be stored in a database or a data frame for further analysis.

## Data cleaning
Once the data is collected, it needs to be cleaned and prepared for analysis. This may involve removing duplicates, handling missing data, converting data types, and merging data from different sources.
## Exploratory data analysis (EDA)
The next step is to perform exploratory data analysis to understand the basic characteristics of the data, such as minimum, maximum, average, median, and standard deviation. This may involve using descriptive statistics, histograms, box plots, and scatter plots to visualize the data and identify any outliers or trends.

## Feature engineering
Feature engineering involves creating new features from existing data, such as calculating the return on investment (ROI) for each movie based on its budget and box office earnings.

## Data visualization
Finally, data visualization techniques such as bar charts to present the results of the analysis in a clear and concise manner. This can help identify patterns and trends that may not be immediately apparent from the raw data.







##  Visualizations
1. Which genres have the most popularity?
The popularity of a movie is an indicator of how much the audience is engaging with the movie and how much attention it is receiving. This can be reflected in factors such as ticket sales, social media mentions, online reviews, and word-of-mouth recommendations. 
![My Image](Images/Top%2010%20most%20Popular%20Genre%20Movies.png)
Overall, the plot suggests that Adult is the most popular genre among moviegoers, followed closely by Romance, Action, Crime, Drama and Comedy.


2. What are the most profitable genres of movies? 

![My Image](Images/Top%2010%20Profitable%20Genres.png)

3. What are the highest rated genres of movies?
![My Image](Images/Top%2010%20Genres%20with%20the%20Highest%20Ratings.png)

4. Should runtime be considered when deciding what types of movies to make?
![My Image](Images/Runtimes%20by%20Genre.png)

5. What is the relationship between movie release month and box office success?
![My Image](Images/Box%20Office%20Performance%20by%20Release%20Month.png)

6. Which studios are performing well?
![My Image](Images/Top%20Studios.png)


##  Limitations

The dataset used for this analysis is limited to movies on IMDb and may not be representative of all movies in each genre. Therefore, the conclusions drawn from this analysis may not be applicable to all movies in a given genre or to the movie industry as a whole.

Categorization: The genres assigned to each movie are based on a single label, and there may be ambiguity or overlap between genres. Additionally, some movies may not fit neatly into any one genre, which could affect the accuracy of the analysis.

Inflation: The data does not account for inflation, which could affect the accuracy of the profit figures, particularly for older movies.

Missing data: The data may not include all relevant variables, such as budget, marketing spend, or demographic information about the audience. This could limit the scope of the analysis and make it difficult to draw accurate conclusions.
##  Recommendations

Consider investing in popular genres: Some genres consistently perform well at the box office, such as action, adventure, and animation. However, be careful not to rely solely on trends and make sure the movie has a unique and compelling storyline.

Consider producing movies in the Drama, Comedy, and Thriller genres, as these genres have the highest total net profit. Additionally, the client may want to avoid producing movies in the Adventure and Mystery genres, as these genres have the lowest total net profit.

Consider producing films in the Documentary or Sports genres, as they tend to receive higher average ratings. However, it's also important to consider the potential profitability of a genre, as we saw in our previous analysis. Therefore, we suggest a balance between producing films in profitable genres like Drama, Comedy, and Thriller, while also exploring the high-rated Documentary and Sports genres.

Movies in the Adult genre have a higher rating than movies in other genres. However, it's important to note that the Adult genre has a very small sample size (only 19 movies), which may limit the generalizability of this finding. It's also important to consider that the term "Adult" is often used to refer to movies with mature or explicit content, which may not be suitable for all viewers.

Consider producing a Biography or Fantasy film, if  looking to produce a movie with a longer runtime, otherwise If producing a movie with a shorter runtime, consider producing a Documentary, Horror, or Western film. If the aim is to target a family audience, consider producing a Family film, which has a relatively high median and mean runtime.


Consider releasing movies during the months of November, December, or June to increase the chances of generating higher revenues.

Aim to work with top-performing studios such as Fox, WB, and MGM, as they have the highest overall worldwide gross.​

