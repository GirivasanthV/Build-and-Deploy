🛍️ Retail Customer Segmentation Dashboard

This project is an interactive Streamlit application for retail customer segmentation using K-Means clustering and Principal Component Analysis (PCA).

🚀 Overview

Customer segmentation is a vital strategy in modern retail analytics, helping businesses understand and target their customers effectively. This project aims to group customers based on purchasing patterns and demographic attributes to support data-driven marketing decisions.

The project employs the K-Means clustering algorithm to discover natural customer groupings and uses PCA for dimensionality reduction and visual interpretation of clusters. The Elbow Method and Silhouette Score are applied to determine the optimal number of clusters, ensuring meaningful segmentation.

✨ Features

The application is organized into four main sections:

Data Overview:

Upload your own CSV data or use the default "Mall Customers" dataset.

View a preview of the data and its statistical summary.

See the automatic identification of numeric and categorical features.

Optimal K Analysis:

Visualize the Elbow Method (Inertia) to find the optimal number of clusters.

Analyze the Silhouette Score to measure cluster separation and cohesion.

Segmentation Results:

Select the number of clusters (K) using an interactive slider.

View a 2D PCA scatter plot visualizing the customer segments.

Analyze the "Cluster Profiles" table, which shows the mean values of numeric features for each segment.

Predict New Customer:

Enter the details for a new customer using a dynamic form.

Get a real-time prediction of which segment the new customer belongs to.

⚙️ How to Run

Clone the repository or download the files.

Install the required dependencies:

pip install -r requirements.txt


Run the Streamlit application:

streamlit run app.py


Open the application in your web browser at the provided local URL (usually http://localhost:8501).

📦 Dependencies

The project relies on the following Python libraries:

streamlit

pandas

numpy

plotly

scikit-learn