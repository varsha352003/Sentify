# Sentify: Sentiment-Aware Book Recommendation System


The primary goal of Sentify is to combine sentiment analysis with a recommendation system to build an intelligent and user-centric platform. By analyzing the sentiment of Amazon book reviews using a BERT model for high accuracy, the system identifies user preferences and provides personalized recommendations.  

How It Works:
1. Data Collection & Preprocessing 
  - Extracting Amazon book reviews dataset.  
  - Tokenizing and preparing the data for the BERT model.  

2. **Sentiment Analysis with BERT**  
   - Using a pre-trained BERT model to give a sentiment score of the reviews on a scale of 1-5.  
   - Fine-tuning BERT on book review data for better accuracy.  

3. Hybrid Recommendation System
   - Sentiment-Based Filtering: Recommends books based on positive user sentiment and preferred book categories.  
   - Collaborative Filtering:Uses user-book interactions to find similar users and suggest books they liked.  
   - Content-Based Filtering: Suggests books with similar genres, authors, or writing styles.  
   - Hybrid Approach: Combines sentiment-based recommendations with collaborative and content-based methods for a more accurate and personalized experience.  

Why Sentify?  
✅ More Personalized:Considers both user preferences and emotions in reviews.  
✅ High Accuracy:Uses BERT for sentiment analysis and a hybrid recommendation model.  
✅ Better User Experience:Bridges the gap between understanding user emotions and offering targeted book suggestions.  


