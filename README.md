# Machinelearning
# YouTube Adview Prediction

## Project Description
This project aims to predict the number of adviews on YouTube videos based on various metrics such as views, likes, dislikes, comments, published date, duration, and category.

## Data Description
The dataset contains metrics and other details of about 15,000 YouTube videos. The metrics include:
- `vidid`: Unique Identification ID for each video
- `adview`: The number of adviews (target variable)
- `views`: The number of unique views
- `likes`: The number of likes
- `dislikes`: The number of dislikes
- `comment`: The number of unique comments
- `published`: The date of uploading the video
- `duration`: The duration of the video (in minutes and seconds)
- `category`: Category niche of each video

## Objective
Build a machine learning regression model to predict YouTube adview count based on other metrics.

## Steps and Tasks
1. Import datasets and libraries, check shape and datatype.
2. Visualize the dataset using heatmaps and plots.
3. Clean the dataset by removing missing values and other inconsistencies.
4. Transform attributes into numerical values and perform necessary transformations.
5. Normalize the data and split it into training, validation, and test sets.
6. Train models using Linear Regression, Support Vector Regressor, Decision Tree Regressor, and Random Forest Regressor.
7. Build and train an artificial neural network using Keras.
8. Evaluate models and pick the best one based on error and generalization.
9. Save the best model and predict on the test set.

## Installation
Clone the repository and install the necessary packages:
```bash
git clone https://github.com/yourusername/youtube-adview-prediction.git
cd youtube-adview-prediction
pip install -r requirements.txt
