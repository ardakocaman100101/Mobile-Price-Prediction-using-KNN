# Mobile-Price-Prediction-using-KNN

In this notebook, I solve mobile price classification challenge using K-nearest-neighbors method. You can find the challenge and the data in Kaggle:

https://www.kaggle.com/iabhishekofficial/mobile-price-classification 

There are 20 features for the mobile phones and the output would be the (scaled) price range. 
The features shows similar properties the distance metric doesn't matter. After the data is split, KNN class is created using sklearn. Find the best predictor K:
- High K overfits
- Low K underfits

So, I used elbow technique for determining the optimal K. 

