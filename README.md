# Advanced-Recommender-System-for-Massive-Open-Online-Courses
- Proof of Concept (PoC) to enhance the learning experience by developing an advanced recommender system. The project explored, compared, and deployed various machine-learning models for offline evaluations.

<img width="1567" alt="streamlit" src="https://github.com/devoeop/Advanced-Recommender-System-for-Massive-Open-Online-Courses/assets/96466460/0ca66965-7ac2-426a-a5bb-abcfd8020f5c">

## Libraries and Technologies Used:
- Data Analysis and Visualization: Pandas, NumPy, Matplotlib, Seaborn, WordCloud
- Machine Learning Models: K-means, PCA, K Nearest Neighbors, NMF, Neural Networks (TensorFlow), Linear Regression, Logistic Regression, Decision Tree, Random Forest, SVM, Bagging
- Collaborative Filtering Techniques: Matrix Factorization (NMF), Neural Networks for Latent Feature Extraction
- Web App Deployment: Streamlit

![workflow](https://github.com/devoeop/Advanced-Recommender-System-for-Massive-Open-Online-Courses/assets/96466460/ec6a697a-2b41-4caf-8807-c821c8b3fca8)

## Project Workflow:
1. Data Exploration and Understanding (Keywords and Genres):
- Identified course title keywords using WordCloud.
- Explored online course enrollment datasets, performing exploratory analysis.
- Determined and visualized popular course genres.

![word_cloud](https://github.com/devoeop/Advanced-Recommender-System-for-Massive-Open-Online-Courses/assets/96466460/adeabae7-ae92-4e01-9f9f-37cd13ebedec)

2. Feature Engineering and Similarity Calculations:
- Extracted Bag of Words (BoW) features from course content.
- Calculated course similarity using BoW features.
- Created a robust course BoW dataset for content-based recommendations.

3. Clustering and Dimensionality Reduction:
- Conducted k-means clustering on user profile features.
- Applied PCA for dimensionality reduction.
- Implemented k-means clustering on PCA-transformed components.

4. Content-Based Recommender Systems:
- Generated personalized course recommendations based on enrollment history.
- Leveraged a course similarity matrix for recommending new courses.
- Engineered user profiles based on course genres and ratings.

5. Collaborative Filtering Models and Neural Networks:
- Trained neural networks with an RMSE of 0.0953 on the training set and 0.1254 on the validation set.
- Achieved high accuracy across logistic regression, decision tree, random forest, SVM, and bagging models (Accuracy: 95.45%).
- Implemented collaborative filtering using NMF with an RMSE of 0.2058.
- Built regression models with competitive RMSE metrics for ridge (0.2097), lasso (0.2104), and elastic net (0.2104).

6. Web App Deployment:
- Built a user-friendly web app using Streamlit for seamless model deployment.
- Enabled users to interact with and experience the recommender systems.
