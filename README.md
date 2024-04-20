# Book Recommender System
![Cover](https://github.com/Torin99/Book-Recommender-System/assets/87572723/e37601ec-76de-4629-8114-7f01c15e8147)

## ⁉️ Overview:
This project aims to develop a book recommender system using knowledge-based and reinforcement learning techniques. The system utilizes a dataset containing information about books, ratings given by users, and user demographics.

## 📈 Dataset:
The dataset comprises three CSV files:
1. **Books.csv**: Contains information about various books, including ISBN, title, author, publication year, publisher, and other attributes.
2. **Ratings.csv**: Includes data on user ratings for specific books, indicated by user IDs, book ISBNs, and ratings.
3. **Users.csv**: Contains user information such as IDs, demographic details (e.g., location, age), and possibly other user-related attributes.

## 🛠️ Implementation:
The project involves two main recommendation approaches:

### 🧠 1. Knowledge-Based Recommendation:
   - **Data Preprocessing**: Null values are removed, and book attributes are converted to suitable data types.
   - **Creation of a User-Book Rating Matrix**: A sparse matrix is constructed to represent user ratings for books.
   - **Similarity Calculation**: Cosine similarity is computed between users based on their ratings.
   - **Recommendation Generation**: Top-rated books by similar users are recommended to the target user.

### 🪖 2. Reinforcement Learning Recommendation:
   - **Data Preprocessing**: Null values are handled, and data is preprocessed for reinforcement learning.
   - **Q-Learning Agent**: A Q-learning agent is implemented to learn from user interactions and make personalized recommendations.
   - **Custom Environment**: A custom environment is defined for the agent to navigate and learn from user feedback.
   - **Recommendation Process**: The agent suggests books based on learned preferences and previous user feedback.

## 📂 Files Included:
- **Presentation Slides**: Contains an overview of the project, dataset, implementation details, challenges faced, and future improvements.
- **Reinforcement-Learning.ipynb**: Jupyter Notebook implementing the reinforcement learning-based recommendation system.
- **Knowledge-Based.ipynb**: Jupyter Notebook implementing the knowledge-based recommendation system.
- **Books.csv**: Dataset file containing book information.
- **Ratings.csv**: Dataset file containing user ratings for books.
- **Users.csv**: Dataset file containing user information.

## ⚙️ Requirements:
- Python 3.x
- Libraries: pandas, numpy, scikit-learn, scipy, gym

## 🕹️ Usage:
1. Ensure all required libraries are installed.
2. Open and run the Jupyter Notebooks (Reinforcement-Learning.ipynb, Knowledge-Based.ipynb) to view the implementation and results.
3. Explore the dataset files (Books.csv, Ratings.csv, Users.csv) to understand the data structure and attributes.
