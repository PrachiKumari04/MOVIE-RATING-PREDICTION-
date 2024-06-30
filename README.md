

Movie Rating Prediction

Overview- 
This project uses machine learning to predict the rating of a movie based on various features such as genre, director, actors, and year. The goal is to analyze historical movie data and develop a model that accurately estimates the rating given to a movie by users or critics.

Dataset-
The dataset used is the IMDb Movies India dataset, which contains information on movies, including genre, director, actors, year, and rating.

Features
- Genre: The genre of the movie (e.g., Action, Comedy, Drama)
- Director: The director of the movie
- Actors: The actors in the movie
- Year: The year the movie was released
- Rating: The rating given to the movie by users or critics

Preprocessing
- Handling missing values: Missing values in the dataset are handled using appropriate methods (e.g., mean, median, imputation)
- Encoding categorical variables: Categorical variables (e.g., genre, director, actors) are encoded using LabelEncoder
- Scaling/normalizing numerical variables: Numerical variables (e.g., year) are scaled/normalized using StandardScaler

Feature Engineering
- Genre: The genre feature is extracted and transformed into a numerical representation using TF-IDF
- Director: The director feature is encoded using LabelEncoder
- Actors: The actors feature is encoded using LabelEncoder
- Year: The year feature is scaled/normalized using StandardScaler

Model Selection
- Linear Regression: A linear regression model is trained on the preprocessed data to predict the rating

Evaluation
- Mean Squared Error (MSE): The MSE is calculated to evaluate the performance of the model
- R-squared: The R-squared value is calculated to evaluate the goodness of fit of the model
- Mean Absolute Error (MAE): The MAE is calculated to evaluate the performance of the model

Visualization
- Distribution of Ratings: The distribution of ratings is visualized using a histogram
- Predicted vs. Actual Ratings: The predicted ratings are plotted against the actual ratings using a scatter plot
- Residuals: The residuals are visualized using a histogram
- Feature Importance: The feature importance is visualized using a bar plot

Prediction
- New Movie: A new movie is defined with its features (genre, director, actors, year)
- Prediction: The rating of the new movie is predicted using the trained model

Requirements
- Python: 3.8+
- Pandas: 1.3+
- NumPy: 1.21+
- Matplotlib: 3.4+
- Seaborn: 0.11+
- Scikit-learn: 1.0+

Author-
Prachi kumari (prachikumari2804@gmail.com)
