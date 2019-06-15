# Natural Language Processing and Wine Reviews

__What is the data?__

What we have here is over one hundered thousand wine reviews scraped from the Wine Enthusiast magazine, collected from [kaggle](https://www.kaggle.com/zynicide/wine-reviews). This data has grown in popularity for its popularity as training grounds for a wide variety of machine learning algorithm, such as classifiers, clustering algorithms, and natural language processing.

The reason why this data has become popular regards its size and depth. Each reveiw has several potential labels (reviewer, wine title, country of origin et al) accompanied by a paragraph of text written by an author. This dataset can be used to test linguistic models (classifying authorship of each review given the review's syntax/lexicon), supervised and unsupervised clustering algorithms (wine types/review types) and many other project ideas.
 
 The raw dataset contains thirteen columns; however, we only need to make use of the following four:
 
 + Description: The body of text associated with the reveiw
 + Taster Name: The author of the body of text
 + Points: The rating (0 - 100) given by the taster to the given wine
 + Price: The base price of the wine per bottle
 
__Goal__

Suppose we are a winery looking to optimize our profits by making a wine that is a hit with the critics and sold at a competitive price point. We can attain this goal by exploring the relationship between the attributes most emphasized by the reviewers in their descriptions and the points-to-price ratio.
