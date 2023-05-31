# **Football Team Clustering Analysis: Unveiling Playing Styles in English Premier League and La Liga**


This repository contains the code and analysis for a football team clustering project. The project aims to unveil distinct playing styles exhibited by top clubs in the English Premier League (EPL) and La Liga using clustering techniques.


## **Clustering Methodology**

The clustering analysis is performed using the K-means clustering algorithm, a popular unsupervised learning technique. The dataset used for clustering includes features such as possession, short passes per game divided by long balls per game (SPPLBP), and non-penalty expected goals difference (npxGD). These features are used to identify similar patterns and group the teams into clusters based on their playing styles.

The following steps are involved in the clustering methodology:

1. Data Preprocessing: The dataset is prepared by cleaning and transforming the raw data to ensure its suitability for clustering analysis.

2. Feature Selection: Relevant features are selected from the dataset to capture the essential characteristics of team playing styles.

3. Standardization: The selected features are standardized to ensure that they have comparable scales and contribute equally to the clustering process.

4. K-means Clustering: The K-means algorithm is applied to the preprocessed data, partitioning the teams into K clusters based on their similarity in playing styles.

5. Cluster Interpretation: The clusters obtained from the analysis are interpreted and described, providing insights into the distinct playing styles exhibited by the teams.

## **Requirements**

To run the code and reproduce the clustering analysis, the following requirements should be met:

 - Python (version 3.x)
 - Jupyter Notebook or JupyterLab
 - Required Python libraries: numpy, pandas, scikit-learn, matplotlib, seaborn

It is recommended to set up a virtual environment and install the required libraries using the provided requirements.txt file. The file can be used to install the necessary dependencies by running the following command:


```
pip install -r requirements.txt
```

## **Usage**

...


## **Contributing**

If you wish to contribute to this project, you can fork the repository, make the desired changes, and submit a pull request. Contributions, suggestions, and feedback are welcome!


## **License**

This project is licensed under the (MIT License) [https://opensource.org/license/mit/].


Please note that the actual data used for the analysis may be subject to different licenses or restrictions. Ensure that you comply with the appropriate terms and conditions when using or sharing the dataset.

For any questions or inquiries, please contact the project maintainers (LinkedIn)[https://www.linkedin.com/in/amyrmahdy/].



Author: **amyrmahdy**

Date: **26 May 2023**

