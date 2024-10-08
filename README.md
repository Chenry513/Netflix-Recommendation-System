# Netflix Recommendation System

This project involves building a recommendation system that suggests movies based on user preferences. The system uses collaborative filtering techniques to analyze user ratings and recommend movies that align with the tastes of similar users. The model was developed using Python, Flask, and JavaScript, and it integrates with The Movie Database (TMDb) API to fetch additional movie details like ratings, genres, and cast information.

The recommendation system processes and cleans data from large datasets, including over 5,000 lines of data across 6 CSV files. The web interface, built with Flask and enhanced with HTML and CSS, allows users to interact with the recommendation system in real-time, providing a seamless and intuitive experience. This project showcases the practical application of machine learning in a real-world scenario, creating personalized recommendations that enhance user experience.

## How to Run

To run this project, follow these steps:

1. **Clone the Repository:**
   - Clone the repository to your local machine using the following command:
     ```bash
     git clone https://github.com/Chenry513/Netflix-Recommendation-System/tree/master
     ```

2. **Install Dependencies:**
   - Navigate to the project directory and install all required packages using `pip`:
     ```bash
     pip install -r requirements.txt
     ```

3. **Run the Application:**
   - Start the application by running the following command:
     ```bash
     python main.py
     ```
   - Open your web browser and go to [http://127.0.0.1:5000/](http://127.0.0.1:5000/) to view the project.

By following these steps, you will be able to set up and run the Netflix Recommendation System on your local machine.


## Visual Representation

Here is a visual walkthrough of how the Netflix Recommendation System works:

### 1. Searching for a Movie
![Search for a Movie](search_movie.png)

### 2. Viewing Movie Details
![View Movie Details](view_movie_details.png)

### 3. Viewing Actors & Actresses
![View Actors & Actresses](cast.png)

### 4. User Reviews
![User Reviews](reviews.png)

### 5. Recommended Movies for You
![Recommended Movies](reccomendation.png)

## Technologies Used

- **Python**: For the backend logic and data processing.
- **Flask**: To create the web framework and serve the application.
- **JavaScript**: For dynamic content and interactive user interfaces.
- **HTML/CSS**: For structuring and styling the web pages.
- **TMDb API**: To fetch detailed movie information like ratings, genres, and cast.
- **Pandas**: For data manipulation and preprocessing of movie datasets.





