# Movie Recommendation App

## Overview

The Movie Recommendation App is a simple web-based application that allows users to explore movies by various categories. Users can browse popular movies, get genre-based recommendations, search for movies, and view random movie suggestions. This app uses The Movie Database (TMDB) API to fetch movie data.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Features

- **Popular Movies**: Displays a list of currently popular movies.
- **Genre-Based Recommendations**: Allows users to view movies based on their preferred genre.
- **Random Movie**: Displays a random movie suggestion from the TMDB database.
- **Search Functionality**: Enables users to search for specific movies by title.

## Demo

You can check the live demo of the project [here](https://rabumaabraham.github.io/movie-recommendation-app/)

## Technologies Used

- **HTML**: For structuring the web pages.
- **CSS**: For styling the app.
- **JavaScript**: For app functionality and interactivity.
- **TMDB API**: For fetching movie data.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/rabumaabraham/movie-recommendation-app.git
    ```

2. **Navigate into the project directory**:

    ```bash
    cd Movie Recommendation App
    ```

3. **Create a config.js file**:
   Inside the project, create a folder named js if it doesn't already exist.
   Within the js folder, create a file called config.js.

5. **Get your API Key**:
   Visit the ![TMDB](https://www.themoviedb.org/) website.
   Create an account if you haven't done so.
   Go to the API section, generate an API key, and copy it.

6. **Configure the API Key in config.js**:
   Open config.js and add the following code, replacing "your_api_key_here" with your actual API key:
   const API_KEY = "your_api_key_here";

7. **Open the project**:
   Use a live server to run the project for the best experience.

## Usage

1. Browse through the list of popular movies.
2. Select a genre to see related recommendations.
3. Use the search bar to find specific movies.
4. Click on a movie to view details, ratings, and manage favorites.


## Screenshots

![image](https://github.com/user-attachments/assets/37cc49ee-db19-4928-b8ac-a652fb1c992e)


## Contributing

Contributions are welcome! If you would like to improve this project, follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit the changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Create a pull request.
