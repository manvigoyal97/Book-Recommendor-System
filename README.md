# Book-Recommendor-System
Built recommender system on web scraped goods to provide relevant and personalized book recommendations to the user based on their interests using KNN and collaborative filtering. This feature can help to increase the web traffic as well as enhance the customer experience. I webscraped data from goodreads.com which contains 10,000 books across multiple genres having user ratings and other attributes.

1) Data Preprocessing: Cleaned the scraped data by removing books with incomplete data for some important attributes.

2) Exploratory Data Analysis: Generated graphs to understand the data better, get better sense of which books, author or genre is most popular on basis of ratings given by customers.
  
3) Building Recommendor System: I utilized following methods to build the recommendor system. For the new user, we leveraged KNN Based Recommendations with Euclidean distance and cosine metrics and for the repeat customers, we used two methods: User based Collaborative Filtering to recommend books based on past user history and Item based Collaborative Filtering using Cosine Similarity, Correlation and Matrix Decomposition. We identified pros and cons of both the methods.

Hence, using this recommender system, we can provide recommendations to both new and repeat users based on their interests.
