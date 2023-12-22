### Mall Customer Segmentation

## Overview
This project focuses on customer segmentation in a mall, aiming to categorize them based on their spending scores. By understanding distinct customer segments, businesses can tailor their marketing strategies and improve customer engagement.

## Data Source
Customer Data: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

## Code Structure
I first perform some data exploration to look for the number of entries and any missing data. Then, I used the elbow method to look for the optimal number of clusters, which was 5. Next, setting the number of clusters to 5, I used a KMeans model to segment the different mall customers based on their spending power. I also use the k-means++ method to initialise centroids instead of doing so randomly to have better results in less time. Lastly, I plot the 5 different segments onto a graph, with the centroids of each cluster bolded and bigger for clarity.

## Findings
The group with the highest nunber of customers are those who have an average annual income and average spending score. Businesses should tailor their marketing strategies to appeal to this group of people.

