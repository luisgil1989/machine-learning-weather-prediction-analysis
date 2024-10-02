# Weather Prediction Using Machine Learning

This project focuses on predicting pleasant weather across multiple European weather stations using various supervised machine learning algorithms. The dataset contains temperature, precipitation, and other climate-related data from cities like Basel, Belgrade, Budapest, and more. The goal of this project is to evaluate the effectiveness of different machine learning models in predicting "pleasant weather" conditions based on these factors.

### Objective:
The project aims to explore the performance of K-Nearest Neighbors (KNN), Artificial Neural Networks (ANN), and Decision Trees in predicting weather conditions, optimizing model parameters, and improving accuracy.

### Data:
- **Source:** A historical dataset containing weather data from various European stations.
- **Preprocessing:** Scaling and optimization were applied to the data to improve model performance and handle potential biases.

### Methods:
1. **K-Nearest Neighbors (KNN):**
   - Tested multiple `k` values to balance overfitting and underfitting.
   - Examined how different k-values affect training and testing accuracy.
  
2. **Artificial Neural Networks (ANN):**
   - Experimented with different network architectures (number of layers and nodes).
   - Tested varying `max_iter` and `tolerance` to optimize performance.
   - Generated confusion matrices to evaluate station-level prediction accuracy.
  
3. **Decision Trees:**
   - Built decision trees for classification.
   - Visualized the decision tree structure and confusion matrices for each weather station.

### Results:
- The models' performance was evaluated using classification metrics such as accuracy, precision, recall, and F1-score.
- Confusion matrices were generated to assess the accuracy of weather predictions across different stations.
- Each algorithm had its strengths and weaknesses, with ANN providing more balanced performance overall.

### Key Findings:
- **Best Model:** The Artificial Neural Network (ANN) provided the best results in predicting pleasant weather across most stations.
- **Scaling Impact:** Scaling the data significantly improved the performance of ANN and KNN models.
- **Station Variations:** Some weather stations showed higher prediction accuracy, while others struggled due to missing or inconsistent data.

### Next Steps:
- Further optimization of hyperparameters for better generalization.
- Explore ensemble methods to combine model strengths.
- Apply additional feature selection methods to improve predictive accuracy.
