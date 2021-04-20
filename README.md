<base target="_blank">

# Data-Mining-Project-3

- Project 3 Report on Google Doc can be obtained from
[http://bit.ly/data-mining-project-3-report](http://bit.ly/data-mining-project-3-report)
- Project 3 Report in PDF version can be obtained at
[Data-Mining-Project-3-Report.pdf](Data-Mining-Project-3-Report.pdf)

## Project Summary

What makes a song so popular that it persists in our cultural consciousness for years to come? We embarked on the task of isolating features and components that distinguish popular songs that make an indelible mark on musical history from those that gain a sizable but ultimately lesser level of renown. To do so, we collected data from the Billboard Year-end Top 100 charts and used Spotify audio features and lyrical content provided by Genius to probe what distinguished the Top Ten from songs that rank lower. We discover that certain acoustic and lyrical features are fairly successful in distinguishing classes of songs from one another, and we are ultimately able to use these features to predict song rankings with moderate accuracy.

## Files and Folders
- [data_scraping.ipynb](data_scraping.ipynb)
    Contains code for scraping data from billboard rankings,
    Genius API and Spotify API.
- [plot_cosine_heatmap.R](plot_cosine_heatmap.R)
    Contains code for plotting a heatmap for cosine similarity.
    Obtained from
    [here](https://github.com/UMCUGenetics/MutationalPatterns/blob/master/R/plot_cosine_heatmap.R)
- [Project 3 Exploration.Rmd](Project-3-Exploration.Rmd)
    Code for exploration data for the project.
    Graphs statistics for data as well.
- [Project-3-Numeric-Features.Rmd](Project-3-Numeric-Features.Rmd)
    Code for exploration of numeric features. Linear Regression, K-Means, DBSCAN
    and Random Forest models were tested.
- [Project-3-Words-Features.Rmd](Project-3-Words-Features.Rmd)
    Code for exploration of words(lyric) features. K-Means and cosine similarity
    models were tested.
- [Project-3-Combined.Rmd](Project-3-Combined.Rmd)
    Code for exploration of numeric features + words(lyric) features.
    Cosine similarity model was tested.

## Obtaining data
- Data can be obtained from the Google Drive Folder
    [http://bit.ly/data-mining-project-3-data](http://bit.ly/data-mining-project-3-data)
- Data can also be downloaded from [data_scraping.ipynb](data_scraping.ipynb).
    However, we preprocessed through many steps manually in order to get the data
    as the data obtained from websites wasn't always in the best format. Further,
    it would require downloading a lot of packages and often debugging parts of
    selenium.
