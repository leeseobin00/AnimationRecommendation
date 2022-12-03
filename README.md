# Animation Recommendation

Predicting what animation tend to get higher vote counts.

Predicting animation revenue and/or animation success based on a certain metric.

Recommending animation to users. 

Apply to other Animation data to Evaluation.

We use the dataset in Kaggle

https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database

https://github.com/varian97/Anime-Recommender-System

# Modeling
### Collaborative Recommender
#### Using Apriori

- Use rating to find clusters of similar users and predict using K average ratings.

- When a user enters the title of a video he or she is watching, the cosine similarity is 
  calculated using a pivot table and the video with the highest similarity is recommended.

### Collaborative Recommender - Item based
#### Using KNN(Cosine similarity)

- Use rating to find clusters of similar users and predict using K average ratings.

- When a user enters the title of a video he or she is watching, the cosine similarity is 
  calculated using a pivot table and the video with the highest similarity is recommended.

### Content Based Recommender
#### Using TF-IDF weighting and Sigmoid_kernel

- TF-IDF, or term frequency-inverse document frequency, is a figure that expresses the 
  statistical importance of any given word to the document collection as a whole. TF-IDF is 
  calculated by multiplying term frequency and inverse document frequency.

- Sigmoid function returns two values, 0 and 1, therefore it is more suitable for binary 
  classification problems. 

# Function Definition

Auto Recommendation System : Recommend()

Parameter : title, main_data, rating_data, full_data, data_id, criterion, split

![image](https://user-images.githubusercontent.com/70849467/204722912-baad6738-7d44-48e3-9048-3124059a594f.png)


# Architecture

![image](https://user-images.githubusercontent.com/70849467/204722670-db073fb6-1979-4192-8a8c-b785ee279051.png)
