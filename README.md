# About the project
This project is a self-study project, its main objective is to help me practice on a real dataset and strength my analysis skills in Python.
It is about cleaning and analyzing Netflix movies and tv shows data, and getting insights about the countries where they were filmed, their ratings and release years.

# About the dataset
This project's dataset is an open-source data from Kaggle.

The dataset contains one "csv" file which has 7787 entries with the following information:

**Type:** Movie or TV Show
**Title:** The name of the movie/tv show
**Director**
**Cast:** The names of the movie/tv show's cast
**Country:** The country(s) which this movie/tv show was filmed
**Date added:** The date when the movie/tv show was added on Netflix
**Release year**
**Rating:** Age-based media reviews
**Duration:** The number of minutes for movies or number of seasons for tv shows
**Listed in:** The category(s) which this movie/tv show is listed in
**Description:** A sentence which describes this movie/tv show on Netflix

# Tools and libraries
This project was done in Python using Jupyter Notebooks.

The libraries used are:

**Pandas and Numpy:** for exploration, cleaning and analysis

**Matplotlib and Seaborn:** for visualizations

# Phases of the project
**1. Data Exploration**
After reading the data I have to explore it, its columns, and the info it contains. So, I've gained information about:

  -The dataset size
  -The datatypes of the columns
  -What each column represents
  -What are the information inside the categorized columns such as **type, listed_in, rating and country.**
**2. Data Cleaning**
After exploring the data, I need to check it if there are any issues.

i.Search for duplicates

  -Fortunately, it has no duplicates.
ii.Search for nulls

  2.1. Columns with few nulls
  
    Solution 1: Get the missing information by searching for them
    Solution 2: Drop them
  2.2. Columns with many nulls

    Solution: I wasn't interested in those columns so I left them as they're
iii.Change the incorrect datatypes into appropriate datatypes

**3. Data Analysis and Visualization**
The questions I was interested to know are:
  i.The percentage of movies and tv shows in this data
      ![image](https://github.com/user-attachments/assets/4a1207db-302b-4048-ae0e-d46e66c4a709)
          
          The dataset has 70.7% of its entries movies and the rest are tv shows.


  ii.The growth of content creations over the years

      ![image](https://github.com/user-attachments/assets/7556a91f-3f16-400b-9245-e5f57d4f91c7)

          The results shows that the year which has the highest number of content creations is 2018 which means that the data may be not complete.

  iii.Monitor content creations along the months

      ![image](https://github.com/user-attachments/assets/fb37c38f-c368-4df8-ad6e-bc0c702a9fea)

          December is the month when the highest number of content occurs.
  iv.The oldest 10 tv series and movies
      4.1. The oldest 10 tv shows
          ![image](https://github.com/user-attachments/assets/d8e151f1-e06e-41f4-a21f-7c3129c05f45)
      4.2. The oldest 10 movies
          ![image](https://github.com/user-attachments/assets/38997bd7-8b40-40f1-8b5b-0eef6cf37b49)

  v.The highest 10 countries contributed in contect creation
      ![image](https://github.com/user-attachments/assets/aa0d28bd-6194-4835-8eab-7c1dc23417c8)

        United States is the top 1 country contributed in both movies and tv shows

  vi.The most frequenct categories
      ![image](https://github.com/user-attachments/assets/37babdd8-3bf7-4fa4-8dc9-01e18ea95ab8)

  vii.Number of movies and tv shows by MPA rating for top 10 MPA ratings
      ![image](https://github.com/user-attachments/assets/e489b631-830a-4c93-99ff-34eca0ea7f8a)




      
