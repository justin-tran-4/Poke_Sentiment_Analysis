# YELP REVIEW SENTIMENT ANALYSIS

### Project Summary
In this project, I will be performing word sentiment analysis using the BERT model on sample Yelp reviews.  The goal of this project is to extract the customers true impression of the restaurant in order to help support business decisions by finding the best place to open a new poke restaurant.

I will be using a postgreSQL server database to store the data and use pyspark to filter the reviews to contain one file with only restaurant reviews.

### Question
Can we accurately classify the sentiment of customer reviews and use it to gain insights about restaurant quality and customer satisfaction?

### Data: Yelp Review dataset 
Review data:
Number of Records: 6,990,280
Number of Attributes: 9
Description: Contains the reviews (text & rating), the corresponding business and user, etc.

Example Record:
review_id: saUsX_uimxRlCVr67Z4Jig
  user_id: 8g_iMtfSiwikVnbP2etR0A
  business_id: YjUWPpI6HXG530lwP-fb2A
  stars: 3.0
  useful: 0
  funny: 0
  cool: 0
  text: Family diner. Had the buffet. Eclectic assortment: a large chicken leg, fried jalapeño, tamale, two rolled grape leaves, fresh melon. All good. Lots of Mexican choices there. Also has a menu with breakfast served all day long. Friendly, attentive staff. Good place for a casual relaxed meal with no expectations. Next to the Clarion Hotel.
  date: 2014-02-05 20:30:30


### Tools
- Hugging Face Transformers (BERT)


### Project Pipeline

1. Perform basic EDA and text preprocessing
2. Set up and run BERT sentiment classification
3. Evaluate model accuracy and compare with baseline (TF-IDF with logistic regression)
4. Visualize sentiment distributions by restaurant/location
5. Suggest optimal areas for poke restaurant based on aggregated sentiment

### Results
