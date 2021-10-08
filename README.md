# AnimeRecommendation
## Summery 

They also appear in places like streaming apps (aka Netflix and Hulu) to help you select a TV show or movie to watch next and on journalism/media websites like Medium to suggest other articles you may like to read, among many other uses. Obviously many e-retailers like Amazon have already been using recommender algorithms for quite some time, but many smaller or newer sites are still in need. There are different varieties of recommenders that base their predictions on different features. This helps with business decisions. Overall, the dataset reflect anime ratings.

## Dependencies
- Python jupyter: 
    - numpy, 
    - seaborn, 
    - panda, 
    - plotly.graph_objects, 
    - matplotlib.pyplot, 
    - re, 
    - csr_matrix, 
    - NearestNeighbors, 
    - TfidfVectorizer

## Object based considerations
- Attributes (from Fulldata):
    - anime_id
    - anime_title	
    - genre	type
    - episodes
    - rating	
    - members	
    - user_id	
    - rating_user
    
- Methods:
  - Merging
  - Finding top 10 Anime based on high rating.
  - Build Visuals for (Distribution of ratings, Steaming, top 10)
  - Building recommendation statistics by using (Pivot, Matrices, Cosine() )
  - Filtering titles and dropping duplicates
  - Buidling recommendation function
  - Give Recommendations.
