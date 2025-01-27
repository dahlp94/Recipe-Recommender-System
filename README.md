# Recipe Recommender System

## About The Project
This project aims to tackle the recommendation problem using a "content-based" approach. The system identifies the most relevant suggestions by calculating high cosine similarity measures based on the text input provided by the user.

Leveraging advanced data science techniques such as Word2Vec, Word Embeddings Neural Networks, TF-IDF, and FunkSVD, the system delivers personalized and relevant recipe suggestions. We hope this serves as an excellent foundation for building a robust recommendation engine to inspire food exploration.

---

## Built With
- **Programming Languages and Tools**:
  - Python
  - Jupyter Notebook
- **Libraries and Frameworks**:
  - Scikit-learn
  - NumPy
  - Pandas
  - Surprise
  - Streamlit

---

## Project Contents
- **Main Files**:
  - Project Structure
- **Data Preprocessing**:
  - Cleaning and preparing the dataset for analysis and modeling.
- **Exploratory Data Analysis (EDA)**:
  - Deriving insights from the dataset.
- **Modeling**:
  - **Phase 1**: Content-based approach.
  - **Phase 2**: Collaborative filtering approach.
- **Web Application**:
  - Interactive recipe recommendation using Streamlit.

---

## Getting Started

### Prerequisites
To get started, ensure you have the following:
- **Python** (and required libraries)
- **Jupyter Notebook**
- **Git**

### How It Works
The Recipe Recommender provides a seamless cooking experience, enabling users to find recipes tailored to their specific cravings effortlessly.

Using plain text input, users can type something like:
`"Your text containing items for a specific recipe."`

The system then analyzes the input, suggesting the top five recipes based on ingredient similarity, descriptions, and personalized insights. The results are displayed through a user-friendly web application.

---

## Key Learnings

### Data Cleaning
Although the Kaggle dataset was well-structured, some columns required cleaning to facilitate analysis and model building. Outlier detection and removal were achieved using visualization tools to identify distribution anomalies. In cases where sufficient information was unavailable, outliers were retained to avoid data loss.

### Exploratory Data Analysis (EDA)
Standard statistics like counts, averages, and modes offered limited insights. Advanced exploration revealed popular recipes among users and mapped periods of high and low activity on the food.com website using time series plots.

### Machine Learning Techniques
- Implemented content-based models using Word Embeddings and TF-IDF to understand text data and generate recommendations based on user input.

### Collaborative Filtering and Personalization
- Developed a FunkSVD-based collaborative filtering model to create personalized recommendations by incorporating user search history and ratings.

### Deployment with Streamlit
- Successfully deployed the recommendation system using Streamlit, enabling an interactive and user-friendly interface for real-world use.

---

## Future Directions
- Enhancing the collaborative filtering model with deep learning techniques.
- Incorporating more user feedback to refine recommendations.
- Expanding deployment to mobile platforms for a broader reach.

---

## Conclusion
The Recipe Recommender System is a versatile project that combines data cleaning, EDA, machine learning, and deployment to provide a personalized and interactive culinary experience. It is an ideal starting point for building advanced recommendation engines and exploring the potential of machine learning in real-world applications.

