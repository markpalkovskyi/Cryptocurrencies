# Cryptocurrencies
![](https://user-images.githubusercontent.com/101672943/186331543-6f996dbf-0a7c-4302-a638-9c2ef9513bac.jpeg)

## Project Overview
For this analysis I will create an analysis for the clients who are preparing to get into the cryptocurrency market.
The task is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.

## Process & Result
### Deliverable #1 steps
![](https://user-images.githubusercontent.com/101672943/186333105-4d5f0a6d-efb5-4ad6-81af-98639c5a2f6d.png)
![](https://user-images.githubusercontent.com/101672943/186333228-77466ec9-8fa0-4d8d-8f41-2f9c920763e5.png)
![](https://user-images.githubusercontent.com/101672943/186333265-ca8c56ea-e802-447a-8f2d-3eea6b4a91ff.png)
![](https://user-images.githubusercontent.com/101672943/186333300-a0a458fe-a1b3-49c3-8e75-c4371ce179d1.png)

### Deliverable #2 steps
![](https://user-images.githubusercontent.com/101672943/186333592-42b01d1f-c0be-410e-a2f1-6683a03534b5.png)
^^ applying the Principal Component Analysis (PCA) algorithm to reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

### Deliverable #3 steps
![](https://user-images.githubusercontent.com/101672943/186334074-48dac891-feca-4204-985c-247cf9979416.png)
^^ K-means algorithm to create an elbow curve using hvPlot to find the best value for K.

### Deliverable #4 (final result) steps
* Create a scatter plots with Plotly Express and hvplot for visualize the distinct groups that correspond to the three principal components.
![](https://user-images.githubusercontent.com/101672943/186334330-f37c1d10-916c-4be7-8e0c-fba2c80e35cd.png)
^^ Created 3D scatter plot using the Plotly Express ( scatter_3d() ) function to plot the three clusters from the clustered_df DataFrame.
![](https://user-images.githubusercontent.com/101672943/186334631-a7db0e71-df86-41d0-abb2-479c402533f7.png)
^^ a table with all the currently tradable cryptocurrencies using the ( hvplot.table() ) function.
![](https://user-images.githubusercontent.com/101672943/186334726-e9cf5828-c6ec-49ff-a481-1e6772dfedd4.png)
-Final scatter plot-


