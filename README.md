# Movie Recommendation System

> **Note:** This project was developed in collaboration with 
> [@razafimanantena23](https://github.com/razafimanantena23). 
> My contributions cover the TF-IDF search engine, the collaborative 
> filtering recommendation system, and the Tkinter GUI.

## Table of Contents

1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Features](#features)
6. [Data](#data)
7. [Recommendation Systems](#recommendation-systems)
8. [Challenges](#challenges)
9. [Next Steps](#next-steps)

## 1. Introduction

Welcome to the Movie Recommendation System project! This project is designed to help users discover new movies based on their preferences and the preferences of similar users. It utilizes machine learning algorithms to provide personalized movie recommendations.

## 2. Project Overview

The Movie Recommendation System is built using Python and various libraries and tools, including pandas for data handling, scikit-learn for machine learning, and Tkinter for the graphical user interface (GUI). The system allows users to enter the title of a movie they like, and it provides a list of recommended movies based on user ratings and movie similarities.

## 3. Installation

To get started, follow these installation steps:

### Requirements:
The installation of the following packages is required:
- Beautiful Soup
- Selenium
- Sklearn
- Numpy
- Hashlib
- Pandas
- Tkinter

In addition, it is necessary to download the proper driver for the Chrome browser according to the user's operating system.

1. Clone the repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.

Please ensure that you have downloaded the appropriate Chrome driver based on your operating system before running the project.

## 4. Usage

To use the Movie Recommendation System:

- Run the provided Python scripts -> Recommandation_System_Script.
- Enter a movie title to receive personalized recommendations.
- Click on a movie title in the recommendations to open its IMDb page for more information.

## 5. Features

The Movie Recommendation System offers the following features:

- Utilizes a TF-IDF matrix as a search engine.
- Implements a collaborative-based filtering recommendation system.
- User-friendly GUI for input and recommendations.
- Personalized movie recommendations based on user preferences.
- Clickable movie titles to open IMDb pages for more information.

## 6. Data

The project utilizes two datasets obtained by scraping the IMDb website:

- `movies.csv`: Contains movie information such as title, genre, and IMDb URL..
- `ratings.csv`: Contains user ratings for movies, including user IDs and movie IDs..

## 7. Recommendation Systems

A recommendation system is a system that filters all videos or movies based on user preferences and watch history and provides recommendations to users. There are three types of recommendation systems:

1. Demographic Filtering.
2. Content-Based Filtering.
3. Collaborative-Based Filtering (the system used in this project).

Our recommendation system calculates a score, which is a fraction representing the difference between the movie recommendations of similar users and the recommendations of all users. This approach aims to suggest movies with significant differences in how they are recommended between people similar to us and the entire user base.

## 8. Challenges

During the development of this project, several challenges were encountered, including:

- Web scraping took a significant amount of time due to the size of the IMDb website.
- User IDs could not be scraped from IMDb, requiring a workaround.
- Matching the movies dataset with the ratings dataset was necessary to obtain user ratings.

## 9. Next Steps

Future improvements and enhancements for the Movie Recommendation System could include:

- Using movie genres as an additional filter or search criterion.
- Leveraging more metadata to improve the quality of recommendations.
- Enhancing the user interface for a more visually appealing experience.

Feel free to explore and enjoy the Movie Recommendation System!

