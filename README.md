# Movie-Recommendation-System

This project is a movie recommendation system that suggests movies to users based on their preferences and past interactions. It employs collaborative filtering and content-based filtering techniques to provide personalized recommendations. The system leverages the power of data science and machine learning to analyze user data and movie metadata for accurate suggestions.

## Features

1) Collaborative Filtering: Utilizes user-item interactions to recommend movies similar users have enjoyed.
2) Content-Based Filtering: Uses movie metadata (such as genres, directors, and cast) to recommend movies with similar attributes.
3) Hybrid Model: Combines both collaborative and content-based filtering to enhance recommendation accuracy.
4) Interactive Interface: A user-friendly interface to input preferences and receive recommendations.
5) Data Handling: Efficiently processes large datasets to provide real-time recommendations.
   
## Dataset

The system uses the MovieLens dataset, a well-known dataset in the recommendation system domain. The dataset includes:

User ratings for various movies.
Movie metadata such as genres, release year, cast, and crew.


## Requirements

Python 3.x
Pandas
NumPy
Scikit-learn
Surprise (for collaborative filtering)
Jupyter Notebook

## Installation
Clone the repository:

```bash
git clone https://github.com/RohitMukkala/Movie-Recommendation-System.git
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Open the Colab/Jupyter Notebook:

```bash
jupyter notebook Movie_Recommendation_System.ipynb
```

## Usage

Load the dataset and preprocess it as per the instructions in the notebook.
Choose the recommendation technique (collaborative, content-based, or hybrid).
Input user preferences or select a user ID for recommendations.
Run the recommendation algorithm to get movie suggestions.

## Results
The notebook provides detailed steps and explanations on how the recommendation system works, along with the evaluation metrics to assess its performance. The results section showcases the recommended movies based on the chosen technique.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to create an issue or submit a pull request.
