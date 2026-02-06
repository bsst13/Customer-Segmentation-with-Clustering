# Strategic Customer Segmentation: Optimizing Marketing ROI

## 🎯 The Business Challenge
treating every customer the same is a recipe for wasted marketing budget. This project analyzed a transnational e-commerce dataset (950k+ rows) to move the company from "Mass Marketing" to "Precision Targeting."

## 🚀 The Solution: A Data-Driven Early Warning System
I engineered a behavioral clustering model using **K-Means** to group customers based on five critical metrics:
* **Recency:** How recently they shopped (Churn risk)
* **Frequency:** How often they shop (Loyalty)
* **Average Unit Cost:** Preference for luxury vs. value items
* **Age:** Demographic alignment
* **CLV (Customer Lifetime Value):** Long-term profit potential

## 📈 Key Insights & Business Impact
* **The 62% Realization:** Discovered that over half of the customer base contributed less than 15% of total profit. 
* **The "Champions" Segment:** Identified a high-value group that shopped 3x more frequently than average, representing a prime opportunity for a loyalty program.
* **The "Dormant Giants":** Found a segment of high-spenders who haven't shopped in 6+ months, triggering a recommended "Re-engagement" campaign.

## 🛠️ Technical Stack
* **Clustering:** K-Means (Optimized via Elbow Method & Silhouette Scores)
* **Dimensionality Reduction:** PCA & t-SNE for 2D visualization of 5D data.
* **Libraries:** Scikit-learn, Pandas, Seaborn, Matplotlib.

## 📊 Visualizations
*<img width="767" height="553" alt="image" src="https://github.com/user-attachments/assets/b8d8ff1f-8075-42be-b015-c77d7e8cf080" />
)*
> "By reducing 5D behavioral data into a 2D t-SNE plot, we can clearly see the 'islands' of customer types, providing a visual map for the marketing team to follow."
