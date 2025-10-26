# cosmetics-recommendation
This project is about helping people choose cosmetics. There are many products, so people get confused. I used machine learning to make a system that suggests products. I used K-Means algorithm to group similar users and products.
PROJECT DESCRIPTION
The Cosmetic Recommendation System is a machine learning-based project developed to suggest suitable cosmetic products to users according to their preferences and skin type. The main goal of this project is to analyze product and user data to provide personalized recommendations, improving customer satisfaction and helping users make better purchasing decisions.

DATA SOURCE
The dataset contains details of cosmetic products and their suitability for various skin types. Data was sourced from Kaggle and augmented using web scraping from cosmetic e-commerce platforms like Sephora, Ulta and Nykaa. Key fields include:
1) Label: Classification or target variable.
2) Brand: Name of the cosmetic brand.
3) Name: Product name.
4) Price: Product cost.
5) Rank: Popularity or customer rating.
6) Ingredients: List of active ingredients.
7) Combination, Dry, Normal, Oily, Sensitive: Suitability for different skin types.

This data was cleaned and preprocessed to remove duplicates, handle missing values, and encode categorical values. It enabled effective feature selection and training of the recommendation model.

ALGORITHM
The core algorithm used in this project is K-Means Clustering, an unsupervised machine learning technique for grouping data based on similarity. K-Means aims to partition the dataset into K clusters such that each data point belongs to the cluster with the nearest mean. The algorithm follows these steps:
1) Select the number of clusters (K).
2) Randomly initialize K centroids.
3) Assign each data point to the closest centroid.
4) Recalculate the centroids as the mean of all points in each cluster.
5) Repeat steps 3 and 4 until centroids do not change significantly.

In this project, K-Means clusters users based on their skin type compatibility, product preferences and ratings. This grouping helps recommend relevant products from each user's cluster. The Elbow Method was used to determine the optimal number of clusters. K-Means is simple, scalable and effective for large datasets, making it a suitable choice for this use case.

<img width="859" height="470" alt="image" src="https://github.com/user-attachments/assets/d6ebf66e-e8d1-4b80-b469-df0f4a3dc7cf" />

WORKFLOW NODES
1) Data Collection – Gather product and skin type data.
2) Preprocessing – Clean and prepare the dataset.
3) Feature Engineering – Select key attributes.
4) Model Training – Apply K-Means clustering.
5) Cluster Analysis – Identify user segments.
6) Recommendation Generation – Recommend products from cluster.
7) Evaluation – Validate recommendation quality.

CONCLUSION
The project successfully demonstrates how unsupervised learning techniques like K-Means can be applied to personalize cosmetic product recommendations. By segmenting users into meaningful clusters, the system provides targeted suggestions that cater to specific needs and preferences. It enhances user experience and supports businesses in delivering relevant product offerings.

<img width="584" height="433" alt="image" src="https://github.com/user-attachments/assets/5c7b9958-6ca5-4dfb-90b3-f78239714921" />

REFERENCES
1) Kaggle Dataset: [Cosmetic Products Dataset]
2) Scikit-learn Documentation
3) Google Colab Official Docs
4) Python Libraries: Pandas, Numpy, Matplotlib
5) Research papers on clustering and recommendation systems
6) Tutorials on K-Means algorithm and unsupervised learning

OUTPUT:

<img width="558" height="219" alt="image" src="https://github.com/user-attachments/assets/abcd42c8-46f9-4251-b100-2cf3d2296c0e" />




