# Movie Industry: Exploratory Data Analysis


## Project Description

This project involves analysis of movie data to determine which factors contribute to successful movies. This is not a comprehensive, in-depth analysis of all aspects of the data, but it is a good foundation to begin understanding what makes movies successful. The first portion involves importing and cleaning the data, and although not all tables will be used, I preliminarily decided to go through and clean all of them. Once the data is cleaned, there are a few questions that I gleaned from the data followed by my recommendations.

## The Data

The data used for this project was compiled by Flatiron School, and it was pulled from the sources listed below. All tables were cleaned but not all were used in final analysis.

* Box Office Mojo: https://www.boxofficemojo.com
* IMDB: https://www.imdb.com/interfaces/
* Rotten Tomatoes: https://www.rottentomatoes.com
* The Movie Database: https://www.themoviedb.org/?language=en-US

## Objectives

Extract questions and recommendations from the data to determine which factors contribute to making a successful movie. 

## Questions/Visualizations/Recommendations

1. What is a reasonable budget and profit margin for a movie?
    - The average net profit for the top 25 movies is over 1.2 billion
    - The average budget is over 196 million
    (image)
    - Overall picture, budget has a .61 correlation with net profit
    - It seems that the higher the budget, the higher the net profit
    (image)
    - There is less noticable correlation when looking at budget ranges in 100 millions
    - The correlation is completely different for each budget range
    - There are several movies falling into a negative profit range
    (image)
    - It seems that the higher the budget, the higher the deficit for negative net profit movies
    (image)
Answer to Question 1: Determining a budget based on correlation with net profit does not work. In reality, we can get an idea of average budget amounts of other movies, but we can only determine budget based on calculating all potential expenses. What we can determine is a profit margin goal. Based on the median profit margin for all profitable movies, I recommend a profit margin goal of at least 67%. Based on the top 25 movies, we can then create a stretch goal for profit margin at 86%.
(image)

2. Who are the top competitors?
    - By amount of movies made, Universal, Fox, and Warner Bros. are top 3 with over 100 movies made.
    (image)
    - Dreamworks, Buena Vista, Universal, Fox, Warner Bros, and Paramount have the highest net profit all over 1.5 billion
    (image)
Answer to Question 2: I would determine top competitors based on net profit alone, which would be Dreamworks, Buena Vista, Universal, Fox, Warner Bros. and Paramount.
3. Which director/s should be considered to hire?
    - Looking at director experience is necessary as directors with 4 or more movies almost always have a positive net profit.
    (image)
Answer to Question 3: I would recommend directors with 4 or more movies and the highest net profit overall. Joss Whedon, Christopher Nolan, Michael Bay, and Jon Favreau are the top 4 with over 500 million in net profit.
(image)
4. Which genres have the highest net profit?
    - Drama is the most popular genre at over 1400 movies, almost double the amount of Comedy
    - Animation, Musical, and Adventure have the highest average net profit over 200 million each.
    (image)
Answer to Question 4: Choose a combination that is sensible and the most profitable i.e. Animation, Adventure, and Sci-Fi

## Further Study

There are many more factors involved in making movies that we could dive into, whether it be deciding on a cast for the film, how ratings and popularity correlate to net profit, the impact of runtime (if any), domestic gross revenue vs. foreign gross revenue, etc. Additionally, further analysis can involve utilizing multivariate linear regression to determine net profit based on a number of movie features. This project is a good foundation to build upon for further analysis.


