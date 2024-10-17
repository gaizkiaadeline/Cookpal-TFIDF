# COOKPAL Recipe Recommendation System


This project provides a recipe recommendation system that suggests recipes based on the ingredients you have. By analyzing a dataset of recipes, the program computes the similarity between the ingredients you input and those in the dataset to recommend the most relevant dishes.

Features:
- Ingredient Tokenization: The system tokenizes the list of ingredients and normalizes the text by removing unnecessary characters and common terms like "secukupnya" and "sdm."

- TF-IDF Similarity Calculation: We use the TfidfVectorizer from sklearn to calculate the similarity between the user's ingredients and the ingredients from the recipes in the dataset.

- Dataset Combination: The dataset consists of multiple categories, such as chicken, fish, lamb, beef, tofu, eggs, and shrimp, which are combined to form a comprehensive dataset of recipes.

- Top Recipe Recommendations: For each set of input ingredients, the system returns the top 5 most similar recipes.

- Visualization: A bar chart visualizes the similarity scores of the top 5 recommended recipes based on the input ingredients.

Presentation Link: https://www.canva.com/design/DAFcBNjSdKw/O8WR500eyNDZQG4E9FuKCw/edit?utm_content=DAFcBNjSdKw&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
