# Breast Cancer Classification using K-Nearest Neighbors (KNN)  

This project leverages a custom-built KNN algorithm and scikit-learn's KNN implementation to classify breast cancer based on clinical data. The model demonstrates high accuracy and provides insights into the dataset through detailed visualizations and analysis.

## Features  
- **Custom KNN Algorithm**: Implements the KNN classification from scratch with performance metrics.
- **EDA and Visualizations**: Includes histograms, scatter plots, and heatmaps to uncover data patterns.
- **Hyperparameter Tuning**: Optimized KNN parameters using GridSearchCV for better performance.
- **Evaluation Metrics**: Precision (94.44%), Recall (95.77%), F1-Score (95.10%), and Accuracy (93.86%).

## Technologies Used  
- **Python Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn.  
- **Machine Learning Techniques**: KNN algorithm, data standardization, hyperparameter optimization, ROC curve analysis.  

## Key Visualizations  
- Histograms for feature distributions.
- Scatter plots for target feature relationships.
- Correlation heatmap to identify feature interdependencies.

## How to Use  
1. Clone the repository:  
   ```bash
   git clone <repository-url>
   cd breast-cancer-classification-knn
Install required packages:
bash
Copy code
pip install -r requirements.txt
Run the code to train the models and view visualizations:
bash
Copy code
python main.py

Results
Custom KNN Model: Achieved 93.86% accuracy with robust classification metrics.
Scikit-learn KNN: Validated results and optimized using GridSearchCV.

Future Improvements
Explore additional classification algorithms for comparison.
Extend the analysis to include feature selection techniques.
Integrate deployment-ready APIs for model inference.

Acknowledgements
This project uses the Breast Cancer Wisconsin (Diagnostic) Dataset available in scikit-learn.
