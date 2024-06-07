# Movie_Recommendation_System
This repository contains a movie recommendation system using collaborative filtering. The model leverages user and movie embeddings to suggest movies based on user preferences and incorporates additional movie metadata for enhanced recommendations. The dataset used is from MovieLens, consisting of 25 million movie ratings and tag applications.


Got it! Here's a revised README file reflecting the use of collaborative filtering only:

---

# Movie Recommendation System

## Description

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Architecture](#model-architecture)
6. [Results](#results)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The goal of this project is to build a robust movie recommendation system that can provide personalized movie suggestions based on a user's past ratings. By using collaborative filtering, we aim to improve recommendations by leveraging the collective preferences of all users.

## Dataset

The data used in this project is from the [MovieLens dataset](https://grouplens.org/datasets/movielens/), which includes:

- 25 million movie ratings
- One million tag applications
- 62,000 movies
- 162,000 users

We primarily use the `movies.csv` and `ratings.csv` files for building the recommendation model.

## Installation

To run this project, you'll need to have Python and the following libraries installed:

- NumPy
- Pandas
- TensorFlow
- scikit-learn
- Matplotlib
- IPython

You can install the required libraries using `%pip install` magic  function.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/SaintJeane/Movie_Recommendation_System.git
cd Movie_Recommendation_System
```

2. Download the MovieLens dataset and place the `movies.csv` and `ratings.csv` files in the project directory.

3. Run the Jupyter notebook or Python script to train the model and generate recommendations:

```bash
jupyter notebook Collaborative_Filtering_Model.ipynb
```

## Model Architecture

The recommendation system uses a neural network-based collaborative filtering approach. The key components of the model include:

- User and movie embeddings to capture latent factors.
- Dot product of embeddings for user-movie interaction.
- Additional layers for bias and non-linearity.

The model is trained using mean squared error loss and optimized with the Adam optimizer.

## Results

The model provides personalized movie recommendations by leveraging user ratings. The collaborative filtering approach helps improve the recommendation quality by considering the collective preferences of all users.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
