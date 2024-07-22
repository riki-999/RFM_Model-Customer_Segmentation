# Data Mining for a Retail Store
This project uses the RFM model to analyze customer behavior from a retail store's operations and marketing perspective. We group customers using the Hierarchical Agglomerative Clustering method. Here's why and how we do it:

## Built With
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/38/Jupyter_logo.svg/44px-Jupyter_logo.svg.png" width ="60" height="40"/> <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQmbk2Guoy3pIIK3-EqKfAMaUFnCY5zEOq20A&s" width="80" height="40"/> 
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLEK1mnIHzN4-9tI36TSqF84JCPtogifhsAQ&s" width="80" height="40"/>
<img src="https://miro.medium.com/v2/resize:fit:638/1*UoBrVq6F9KmAnnyTHrlCXA.png" width="80" height="40"/>
<img src="https://seaborn.pydata.org/_images/logo-wide-lightbg.svg" width="80" height="40"/>
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b2/SCIPY_2.svg/512px-SCIPY_2.svg.png?20200904111722" width="80" height="40"/>

## But Why Hierarchical Clustering???
1. **Understanding Relationships:**

    Understand how close each data point is to the others, rather than just seeing their overall distribution (like in a scatter plot).
2. **Creating Hierarchies:**

    Help to visualize data in a hierarchy, making complex relationships simpler to understand.
3. **Using Dendrograms:**

    Shows how data points can be grouped at different levels of similarity.
 
   
## Features

- **Recency (R):**
    Identifies customers who have engaged with the store most recently, indicating their likelihood to respond to new marketing efforts.
- **Frequency (F):**    Recognizes loyal customers who frequently shop at the store, highlighting their value to the business.
- **Monetary Value (M):** Identifies high-value customers who contribute significantly to the store's revenue.
  
## Usage

`
Behavioral Patterns: Identify seasonal trends, & purchasing frequency within customer segments.
`

`
Marketing Strategies: Tailor promotions and communication to specific segments based on their behavior and value.
`

`
Customer Lifetime Value (CLV): Focus retention and loyalty efforts on high-value segments.
`

`
Churn Prediction: Develop retention strategies for customers showing signs of reduced engagement or potential churn.
`

`
Product Recommendations: Enhance product suggestions based on the preferences and purchase history.
`

`
Sales Forecasting: Use segmented data to better predict future sales and optimize inventory.
`


## Roadmap
1. **Measure Distance:**
Use Euclidean, Manhattan, or other distance formulas to quantify how close data points are to each other.
<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*VvOVxdBb74IOxxF2RmthCQ.png" width="400" height="300"/>        <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*guOwD01bko5ITVIJWQdIPQ.png" width="400" height="300"/>
</p>

3. **Group Closest Data Points:**
Start by grouping the closest data point to form initial clusters.

4. **Form Higher-Level Clusters:**
Treat each new group as a single unit and find the next closest group to create a higher level in the hierarchy.

5. **Build the Dendrogram:**
Objective: Visualize the clustering process & analyze the hierarchy of clusters and understand the data structure.
6. **Increase Granularity:**
Continue breaking down clusters into smaller units to achieve a finer granularity level, making it easier to analyze data at a detailed level.
<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*o_AumweJUR9g68y5nzo7fg.png"/>
</p>


> **Note:**
>
>When there is no information about how many clusters exist in the dataset, the dendrogram can suggest potential clusters but cannot determine the exact number.


##  Skills
Data Mining, Data Analysis, RFM Analysis, Hierarchical Clustering, Dendrogram, ML Algorithm..........



## Acknowledgements

 - [Understanding Dendrogram](https://medium.com/dssimplified/understanding-hierarchies-using-dendrograms-e3aef7ac5ea4)
 - [Hierarchical clustering explained](https://towardsdatascience.com/hierarchical-clustering-explained-e59b13846da8)
 






