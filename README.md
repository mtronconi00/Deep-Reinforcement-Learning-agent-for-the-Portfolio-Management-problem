**Input data**

- "RAY as of Mar 31 20241.xlsx": includes relevant information on the components of the Russell 3000 index.

- "sample.pkl": rapresentative sample of 100 stocks used for empirical analysis.

- "clusters.pkl": clusters assigned to all the stocks in the sample resulting from a K-means pre-trained model.

- the features observed by the agent shall be retrieved from the "run" code since the file was too heavy to be stored.


**Code**

- "Data preprocessing.ipynb": includes the feature selection process based on mutual information used to obtain 10 relevant technical indicators to be used along with OHLCV data.

- "environment.ipynb": defines how the agent interacts with the environment and the reward function.

- "network.ipynb": includes the proposed policy network architecture based on IIE topology introduced by Liang and others (2017).

- "run.ipynb": defines the MCPG-based training algorithm used in this study.
