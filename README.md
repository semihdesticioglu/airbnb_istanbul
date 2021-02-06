# Airbnb Istanbul Data Analysis

## Table of contents
- [Data Source](#data-source)
- [Installation & Libraries](#installation-and-libraries)
- [About the Project](#about-the-project)
- [File descriptions](#file-descriptions)
- [Results](#results)
- [Example Visuals from Project](#example-visuals-from-project)

## Data Source
Thanks to [InsideAirbnb](http://insideairbnb.com/get-the-data.html) for providing this data.

## Installation and Libraries
You can clone the repo with the code below.
- Clone the repo: `https://github.com/semihnykv/airbnb_istanbul.git`

To be able to run it properly, these libraries should be installed:
>1. Pandas
>2. Scipy
>3. Numpy
>4. Seaborn
>5. Matplotlib
>6. Geopy
>7. Folium
>8. Geopy
>9. Nltk
>10. Wordcloud


## About the Project
In this project, I tried to analyze Airbnb Istanbul data and answer some questions about the data.

Project's scope is explaratory data analysis with visuals and maps, applying statistical test to data to answer the questiones correctly.

All the analyses are can be found on Medium Post : https://semihdesticioglu.medium.com/airbnb-istanbul-data-analysis-40f52e781dac

This project is created as a part of Udacity Data Scientist Nanodegree Program.

## File descriptions

```text
Airbnb Istanbul/
├── airbnb_istanbul_explaratory_data_analyis.ipynb
└── data/
    ├── calendar.csv
    ├──	listings.csv
    └── reviews.csv
└── visuals/
    ├── calendar.png
    ├──	listings.png
    └── reviews.png
```

- airbnb_istanbul_explaratory_data_analyis.ipynb - Explaratory Data Analysis Notebook for Airbnb Istanbul Data.
- data/listings.csv - Listing information of accommodations in Istanbul.
- data/reviews.csv  - Reviews information of accommodations in Istanbul.
- visuals/listings.csv - Listing information of accommodations in Istanbul.
- visuals/reviews.csv  - Reviews information of accommodations in Istanbul.

## Results
* Beyoglu , Sisli, Fatih, Kadikoy and Besiktas have most listing counts, these districts cover 71% of all listings.
* Fatih is the most touristic district area in Istanbul which have most of the sightseeing places and old mosques. Seeing highest hotel rate in this district is not surprising.
* Basaksehir, Bagcilar and Esenyurt has lowest “shared house rate”. In these districts home sharing seems not popular since these areas are more conservative areas.
* Uskudar, Umraniye, Maltepe and Kadıkoy have highest review value score for districts which have more than 50 listings.
95% of the daily price values distributed between 0 and 7276 TL. 103 outlier value is found with 2 std dev. distance from mean.
* Besiktas, Beyoglu, Sisli, Fatih and Kadikoy are evaluated with ANOVA test according to their price mean. At least one group has different mean price according to statistical ANOVA test.
* Continent has an effect on price according to ANOVA test. Rentals located in Europe tend to have higher daily prices.
Besiktas, Beyoglu, Sisli, Fatih and Kadikoy are evaluated with ANOVA test according to their price mean. At least one group has different mean price according to statistical ANOVA test. Kadikoy seem to have lower price range, it’s a good option for tourists:)
* Distances to 8 most touristic places are calculated and minimum value is used for minimum distance feature. Correlation test show no direct correlation. If we assign categories to the locations according to their minimum distance, we can infer that at least one group’s price mean is different than others. Box-plot tells us as the distance to touristic areas increases, mean price decreases.

## Example Visuals from Project 
