# Group22, Big Data Analysis of Google Play Store Applications

Team members:
1. Lotta Kauppinen
2. Jenna Kiviaho
3. Marjaana Koski
4. Jani Laakso
5. Aleksi Savukoski

The chosen dataset contains information of more than 2.3 million applications from Google Play Store. The main goal of this analysis is to find different patterns between the variables. By doing that, we are able to analyze how the different characteristics affect the popularity and ratings.

The analysis also aims to showcase if the free apps outperform the paid apps.

The other goal for this analysis is to showcase how Spark and MongoDB work together in a Big Data Analysis.
   
How to run the project:

1. Download the dataset from Kaggle
    Link to the dataset: https://www.kaggle.com/datasets/gauthamp10/google-playstore-apps

2. Extract the ZIP file and place the Google-Playstore.csv file into the repository's /data folder.

3. Start MongoDB

4. Run the Group_22_data_cleaning.ipynb
    - This notebook cleans the data and stores the processed data into MongoDB.

5. Run the Group_22_analysis_and_visualization.ipynb
    - Execute all cells
    - This is the analysis part of this project

Technologies used in this project:

- Apache Spark
- MongoDB
- Spark SQL
- Pandas
- Matplotlib
- Seaborn
