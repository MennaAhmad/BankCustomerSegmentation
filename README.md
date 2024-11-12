# BankCustomerSegmentation
Project Overview
This project applies machine learning techniques to segment bank customers into distinct groups based on their financial behaviors. By analyzing transaction amounts, account balances, and demographic data, the model provides insights into customer spending patterns, enabling the bank to tailor its marketing efforts, enhance customer satisfaction, and improve retention.

Objectives
The main objectives of this project are:

To categorize customers into budget-based segments (low, medium, high) for targeted marketing and personalized services.
To understand customer behaviors and trends within each segment to inform future banking strategies.
Dataset Details
The dataset includes transaction data with key features such as:

Demographic Data: Age, gender, and location of the customers.
Financial Data: Account balances and transaction amounts.
Behavioral Data: Frequency and timing of transactions.
Preprocessing Steps
Data preprocessing included handling missing values, normalizing features, and preparing the data for clustering and classification.

Technologies and Tools
The following tools and libraries were used:

Python: For data analysis, modeling, and evaluation.
Pandas, NumPy: For data manipulation and analysis.
Scikit-learn: For implementing K-Means clustering and Random Forest classification.
Power BI: For creating an interactive dashboard to visualize customer segments and insights.
Gradio: For deploying an interface to interact with the segmentation and classification models.
Project Workflow
Data Collection and Preprocessing
Collected and cleaned data, handled missing values, and normalized features.

Exploratory Data Analysis (EDA)
Conducted EDA to examine customer behaviors, transaction patterns, and demographic distributions.

Feature Engineering
Created features to represent customer spending habits and demographic attributes.

Modeling

K-Means Clustering: Applied to segment customers into three budget-based groups (low, medium, high).
Random Forest Classifier: Used to predict customer categories based on behavioral and demographic data.
Results & Evaluation
Evaluated the segmentation model’s performance, achieving meaningful clusters that revealed distinct customer profiles. Used silhouette scores to measure clustering quality.

Dashboard & Deployment
Developed an interactive Power BI dashboard to visualize customer segments, and deployed the model using Gradio for easy interaction and interpretation of results.

Results & Insights
Successfully identified three customer segments with distinct spending patterns, which provide actionable insights for targeted marketing.
High-budget customers showed a preference for larger transactions, while low-budget customers had higher transaction frequencies.
These insights enable the bank to design personalized services and improve customer satisfaction across segments.
Usage
The project’s Gradio interface allows users to:

Select multiple customers from a list and view their assigned segments.
Access visualizations of spending behavior for each segment.
Use the interface to make predictions on new data, categorizing customers as low, medium, or high budget.
To run this project locally, ensure that you have Python installed along with the following libraries:

bash
Copy code
pip install pandas numpy scikit-learn gradio
Conclusion & Next Steps
The Bank Customer Segmentation project highlights the value of machine learning in understanding customer behavior. Future improvements could include refining the segmentation model with more data and exploring deeper insights through advanced algorithms.

Contact
For any questions or collaboration opportunities, please reach out to me on LinkedIn or visit my GitHub profile.
