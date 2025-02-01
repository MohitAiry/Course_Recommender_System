# Course_Recommender_System
The Course Recommender System is a machine learning project designed to provide personalized course suggestions based on user preferences, past interactions, and course content for enhanced learning experiences.


## Project Overview
The **Course Recommender System** is a machine learning-based web application designed to help users discover educational courses tailored to their preferences. Users can select from various recommendation models to either obtain suggestions for similar courses or explore recommendations based on their user profile. The project aims to enhance personalized learning experiences by leveraging advanced recommendation techniques.

## Features
- **Model Selection:** Users can choose from multiple recommendation models to get course recommendations.
- **Recommendation Output:** Options to select a single course or multiple courses to receive personalized recommendations.
- **Dynamic Course Discovery:** Enables users to find courses similar to their selected ones, enhancing educational exploration.

## Available Recommendation Models
The following models are implemented in the system, offering diverse approaches to course recommendations:

1. **Course Similarity:** Utilizes content-based filtering by comparing course attributes.
2. **User Profile:** Generates recommendations based on the user’s preferences and interaction history.
3. **Clustering:** Groups courses into clusters based on their features and suggests similar courses from the same cluster.
4. **Clustering with PCA:** Enhances clustering by reducing the dimensionality of course features using Principal Component Analysis (PCA).
5. **K-Nearest Neighbors (KNN):** Recommends courses based on the closest neighbors in the feature space.
6. **Non-Negative Matrix Factorization (NMF):** Decomposes user-course interactions to provide latent feature-based recommendations.
7. **Neural Network:** Applies deep learning techniques to learn complex patterns for course recommendations.
8. **Regression with Embedding Features:** Predicts course preferences using regression models with learned embedding features.
9. **Classification with Embedding Features:** Classifies and recommends courses based on learned feature embeddings.


## Usage Guide
1. **Model Selection:** Choose one of the available models from the dropdown menu in the web application.
2. **Course Selection:** Select a single course or a set of courses to base the recommendations on.
3. **View Recommendations:** Receive and explore the suggested courses.

## Directory Structure
```
course-recommender-system/
├── app/Recommenderapp.py                  # Main web app file
├── app/backend                            # Folder containing recommendation models
├── data                                   # Dataset files
└── README.md                              # Project documentation
```

## Dependencies
The project relies on the following key Python libraries:
- **scikit-learn:** For clustering, KNN, and regression models.
- **numpy:** Numerical computations.
- **pandas:** Data manipulation.
- **streamlit:** Web application framework.
- **tensorflow:** For neural network model implementation.
- **matplotlib & seaborn:** Data visualization.

## Dataset
The project requires a dataset containing course information and user interaction history. Ensure that the dataset is available in the `data/` directory.

## Future Improvements
- Integrate additional deep learning models for enhanced recommendations.
- Implement user feedback mechanisms to refine recommendations.
- Improve UI/UX for better user interaction.
- Include real-time data updates from educational platforms.


