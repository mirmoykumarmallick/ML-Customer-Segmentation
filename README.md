# Customer Segmentation Using Machine Learning

## Project Overview

This project applies unsupervised learning techniques to segment customers into different groups based on their annual income and spending score. The goal is to provide actionable insights for businesses to target specific customer segments more effectively, improving marketing strategies and customer retention.

### **Features**
- **Data Preprocessing**: Handling missing values, feature scaling, and selecting relevant attributes.
- **Clustering**: Using the K-Means algorithm to create customer segments.
- **Dimensionality Reduction**: Applying PCA for visualizing high-dimensional data.
- **Visualizations**: Plotting customer clusters for better understanding of the segmentation.

## Dataset

The dataset contains customer demographic and spending behavior data, including features like:
- **Annual Income (k$)**
- **Spending Score (1-100)**

You can download the dataset from Kaggle or use any customer behavior dataset.

## Technologies Used
- **Python**: Core programming language.
- **Pandas & NumPy**: Data manipulation.
- **Scikit-learn**: Machine learning algorithms and preprocessing.
- **Seaborn & Matplotlib**: Data visualization.
  
## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/mirmoykumarmallick/ML-Customer-Segmentation
2. **Install Dependencies**:
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
3. **Run the Jupyter Notebook**:
   - Open the notebook in Google Colab or Jupyter Notebook.
   - Follow the instructions in the notebook to load the data, preprocess it, and apply K-means clustering.
4. **Evaluate Segmentation**:
   - Use the Elbow method to determine the optimal number of clusters.
   - Visualize the customer segments in terms of PCA components and original features.

## Results
- The K-means clustering algorithm successfully segmented the customers into distinct groups based on their annual income and spending score.
- Each cluster represents a unique customer segment that businesses can target for different marketing strategies, such as upselling, cross-selling, or retention 
  programs.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
- Mirmoy Kumar Mallick
- LinkedIn Profile: linkedin.com/in/mirmoy-kumar-mallick
- Email: mirmoykumarmallick99@gmail.com
