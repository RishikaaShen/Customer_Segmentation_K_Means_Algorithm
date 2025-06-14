### Project: Customer Segmentation and Analysis using K-means algorithm

### About the Project:

Customer segmentation and analysis using K-means algorithm involves grouping customers into distinct clusters based on similarities in their behavior, demographics, or purchasing patterns, enabling targeted marketing strategies and personalized services.

### Objective: 

The main objective of this project is to identify distinct groups of customers based on shared characteristics or behaviors, enabling businesses to tailor marketing efforts, improve customer satisfaction, and optimize resource allocation for each segment.

### Key Activities:

**1.Data Collection:**

Gathering relevant customer data, such as demographics, purchase history, and behavioral metrics.

**2.Data Preprocessing:**

Cleaning and normalizing the data to ensure consistency and remove any outliers.

**3.Feature Selection:**

Identifying the key features (e.g., spending habits, age, or frequency of purchase) to be used in the segmentation.

**4.Choosing K (Number of Clusters):**

Determining the optimal number of clusters (K) using methods like the Elbow method or Silhouette score.

**5.Applying the K-means Algorithm:**

Running the K-means clustering algorithm to partition the data into K clusters based on the selected features.

**6.Interpretation and Action:**

Using the insights from the clusters to inform targeted marketing strategies, product offerings, and personalized experiences.

### 🛠️ Toolkit used for the project: 

The toolkit used for customer segmentation analysis using K-means algorithm typically includes the following:

### 🔄 Framework

**⚙️ scikit-learn**: A comprehensive library of machine learning tools

### 📚 Libraries:

**🔧 pandas:**  Used for data manipulation

**🔧 numpy:** Used for numerical computation

**🔧 matplotlib and seaborn:** Used for data visualization

**🔧 KMeans:** A specific algorithm for clustering data into a predefined number of clusters.

**🔧 silhouette_score:** A metric for evaluating the quality of the clusters formed by a clustering algorithm like K-means.

![image](https://github.com/user-attachments/assets/0bbc1430-51e6-4788-807b-01f8e799e25f)

### After importing the libraries:

Once the required libraries are imported, the next step is to load the CSV file into the environment to begin the customer segmentation analysis.

![image](https://github.com/user-attachments/assets/48363231-0a8a-45b0-82ec-ea0824e88ec3)


Afterward, we perform data collection, where we gather relevant information for the analysis, followed by data preprocessing, which involves cleaning and preparing the data by handling missing values, encoding categorical variables, and normalizing or scaling numerical features. Finally, feature selection is conducted to identify the most important variables that contribute to the model's performance, ensuring a more efficient and accurate analysis.

![image](https://github.com/user-attachments/assets/e0ff6c96-6ef6-4a5e-a4a0-e326a657ddd1)

-📈To visualize the distribution of the "Age" variable in the dataset using a violin plot.

![image](https://github.com/user-attachments/assets/d0d3201a-47c0-4fb2-88bd-6aaf504defbd)

-📈To compare the distributions of two variables, Spending Score (1-100) and Annual Income (k$), using box plots side by side.

![image](https://github.com/user-attachments/assets/92d2ea09-4e94-4493-8515-1396133c721a)

-📈To visualize the distribution of genders in the dataset using a bar plot.

![image](https://github.com/user-attachments/assets/247ca0e4-d611-4752-a9fa-5ab1735c6125)

-📈To visualize the distribution of customers across different age groups using a bar plot.

![image](https://github.com/user-attachments/assets/18b0ad49-f1e0-4481-b1cb-19dd4f725021)

-📈To visualize the distribution of customers across different spending score ranges using a bar plot. 

![image](https://github.com/user-attachments/assets/1e06b843-95af-4da8-91fb-dc42a118231e)

-📈To visualize the distribution of customers across different annual income ranges using a bar plot.

![image](https://github.com/user-attachments/assets/ca83335c-a306-4219-a9ad-7bc5f36facf9)

After performing data collection, data preprocessing, and feature selection, we can proceed with K-means clustering, where the data is grouped into distinct clusters based on similarities in the selected features, allowing us to uncover patterns and segment the customers for further analysis.

**Feature Selection:**

-📈To visualize the relationship between Age, Annual Income, and Spending Score in a 3D space.

![image](https://github.com/user-attachments/assets/cd3c91f1-8df6-4b4c-bf95-db8a7ac71e87)

**Choosing K (Number of Clusters):**

-📈To identify the optimal number of clusters (k) for the K-means clustering algorithm by plotting the Within-Cluster Sum of Squares (WCSS) for different values of k. The Elbow Method helps to determine the point where the WCSS starts to decrease at a slower rate (forming an "elbow"), indicating the most suitable number of clusters for the dataset.

![image](https://github.com/user-attachments/assets/665de296-9133-4eca-a2e4-79170e2cbfa6)

**Applying the K-means Algorithm:**

-📈To apply K-means clustering to group customers based on their Age, Annual Income, and Spending Score into 5 distinct clusters. 

![image](https://github.com/user-attachments/assets/7d3c92e5-c32e-4ab3-a53e-1694818f0f6e)

### Conclusion:

The customer segmentation analysis using K-means algorithm reveals distinct customer groups based on key features such as Age, Annual Income, and Spending Score. By applying K-means clustering, we identified 5 unique segments, each with specific characteristics. These segments provide valuable insights into customer behavior, enabling targeted marketing strategies and personalized product offerings. The visualizations, including 3D scatter plots, clearly show the distribution of customers across these clusters, highlighting the potential for more effective customer engagement. Overall, K-means clustering proves to be a powerful tool for understanding customer demographics and improving decision-making.

