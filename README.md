# Python-Machine-Learning-and-AI-Unsupervised-PCA-Project-on-Facebook-Dataset-

Unsupervised Analysis Project

Case Information

Congratulations! You have just been hired at a marketing consulting firm in Thailand. This is a very interesting market in terms of social media. To get you up to speed, your firm has asked you to read the following research on Usage and Engagement Patterns for Facebook Live Sellers in Thailand Download Usage and Engagement Patterns for Facebook Live Sellers in Thailand.

 

Objective

Your director has tasked you with analyzing the impact of video content. In short, your company has long operated under the general idea that videos are the most engaging form of social media, and that they should advise their clients to create as many of these as they can. 

 

Analysis Tasks/Questions

Provide an introduction to your analysis. (minimum 5 sentences)
In terms of reactions (likes, loves, etc.), how do videos perform when compared to other forms of content? Are they leading in terms of total engagement? What about in engagement on specific reactions? (minimum 10 sentences)
Develop principal components (PCA) based on the available social media metrics in the dataset. You may choose to group or exclude metrics as you see fit. 
Develop a scree plot and determine how many principal components you would like to retain. Draw a vertical line in the scree plot to indicate your cutoff point. Explain your rationale. (minimum 5 sentences)
Present the factor loadings for the retained principal components (correlations with the original features), rounded to two decimal places.
Interpret each of your retained principal components. Remember to interpret both sides of each principal component. (minimum 5 sentences per principal component)
Rename each principal component based on your interpretation of what it represents.
Develop segmentation with k-means clustering, using your retained principal components. You may also include additional features in your segmentation (avoid reusing the features that were used to develop the principal components).
Decide on an ideal number of clusters and explain your rationale. (minimum 5 sentences)
Present and interpret each segment using cluster centroids and give an example of a "normal" post in each segment. (minimum 5 sentences per segment)
Rename each segment based on your interpretation of what it represents.
Analyze the status types of each segment and report any findings related to videos. (minimum 5 sentences)
Develop three logistic regression models (1 = video, 0 = not video), each based on the following x-features.
Model 1: Original x-features
Model 2: Retained principal components
Model 3: Retained clusters
Select your best model from above and present the following:
Your rationale for why this is the best model. (minimum 5 sentences)
Model results: train-test gap based on accuracy and AUC score based on the results of the .predict step)
Confusion matrix: Explain each error and its risks. (minimum 5 sentences)
 

Dataset

facebook_live_data.xlsx Download facebook_live_data.xlsx

 

Deliverables

Submit your Jupyter Notebook (.ipynb format) as well as an .html file representing your final work.
