# Algorithmentor: Personalized Course Recommender System

Welcome to the **Algorithmentor** project repository! This project explores a comprehensive data science framework for developing a multi-faceted course recommender system, designed to scale personalized learning experiences for online education platforms.

## Table of Contents

- [Algorithmentor: Personalized Course Recommender System](#algorithmentor-personalized-course-recommender-system)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Project Structure](#project-structure)
  - [Datasets](#datasets)
  - [Notebooks](#notebooks)
  - [Installation](#installation)
    - [Requirements](#requirements)
    - [Usage](#usage)
  - [Results and Visualizations](#results-and-visualizations)
  - [License](#license)
  - [Disclaimer](#disclaimer)

---

## Project Overview

In the rapidly growing field of online education, **Algorithmentor** aims to enhance user engagement and satisfaction through personalized course recommendations. This project develops multiple recommendation models to address key challenges such as scaling personalization, optimizing content, and predicting user preferences.

The project features several recommendation strategies and predictive models, including:
- **Content-Based Filtering**
- **Collaborative Filtering (KNN and NMF)**
- **Clustering-Based Recommendations**
- **Neural Network-Based Rating Prediction**
- **Regression and Classification Models for Ratings**

These models collectively contribute to a robust, scalable recommendation system tailored to diverse user needs.

## Project Structure

This repository includes the following main components:

- **Presentation**: A presentation summarizing the business case, model approach, and key findings.
- **Datasets**: User and course data files for training and evaluation.
- **Notebooks**: Jupyter notebooks containing detailed steps for data exploration, model development, and evaluation.

**Directory layout:**
```plaintext
Algorithmentor
├── Presentation/
│   └── Algorithmentor_Project_Presentation.pdf
├── Data/
│   ├── user_rating_info.csv
│   └── course_info.csv
├── Notebooks/
│   ├── nb1-eda.ipynb
│   ├── nb2-content-based.ipynb
│   ├── nb3-cluster-based.ipynb
│   ├── nb4-collaborative-based-knn.ipynb
│   ├── nb5-collaborative-based-nmf.ipynb
│   ├── nb6-neural-network.ipynb
│   ├── nb7-regression-based.ipynb
│   └── nb8-classification-based.ipynb
│
└── LICENSE
README.md
```

## Datasets

- **user_info.csv**: Contains anonymized user IDs and interaction details (e.g., ratings).
- **course_info.csv**: Details about each course, including titles, descriptions, and key topics.

The datasets have been processed to ensure compatibility with various recommendation models and to address issues like sparsity and class imbalance.

## Notebooks

Each Jupyter notebook focuses on specific stages of the project:

1. **nb1-eda.ipynb**: Exploratory Data Analysis to uncover user preferences and high-demand course topics.
2. **nb2-content-based.ipynb**: Implements content-based filtering using user-course interactions and course similarity.
3. **nb3-cluster-based.ipynb**: Clustering users or courses to make scalable recommendations.
4. **nb4-collaborative-based-knn.ipynb**: Collaborative filtering using K-Nearest Neighbors.
5. **nb5-collaborative-based-nmf.ipynb**: Collaborative filtering with Non-negative Matrix Factorization (NMF).
6. **nb6-neural-network.ipynb**: Predicts user ratings using neural networks and embeddings.
7. **nb7-regression-based.ipynb**: Rating prediction using regression techniques.
8. **nb8-classification-based.ipynb**: Rating rating prediction using classification models.

## Installation

To run the notebooks locally, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/LeejoAbraham01/project_algorithmentor
    cd Algorithmentor
    ```

2. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

### Requirements

- Python 3.x
- Jupyter Notebook
- Required packages listed in `requirements.txt`

### Usage

1. **Open Jupyter Notebook:**

    ```bash
    jupyter notebook
    ```

2. **Run each notebook in the order listed above** for a complete analysis, from exploratory data analysis to model evaluation.

3. **Modify paths to data files** in the notebooks if necessary.

## Results and Visualizations

The notebooks provide visualizations for user engagement trends, model accuracy, and recommendations for different approaches. Key findings are summarized in the `Algorithmentor_Project_Presentation.pdf` file.

## License

This project is licensed under the MIT License. You are free to share and adapt the work as long as you provide appropriate credit.

## Disclaimer

Algorithmentor is a fictitious entity created solely for educational purposes. Any resemblance to actual companies is purely coincidental. The author(s) of this project assume no responsibility or liability for any use of this fictitious company name or related content by third parties.