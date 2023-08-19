# target_sentiment_analysis
This project aims to utilize the above concept to conduct a sentiment analysis study on customer reviews related to Target, an American retail organization. The reviews under study were scraped from TrustPilot, an online platform where customer reviews are accessible to the public.
The code flow can be summarized as follows:
- Scraping reviews: All reviews used for this project can be found here: https://www.trustpilot.com/review/www.target.com
- Bag of Words: To start with, the code creates a bag of words implementation for all reviews collected and creates a term frequency - inverse document frequency sparse vector.
- Modelling & Prediction: The code then considers a number of modelling techniques to predict if reviews are positive or negative. Evaluation is conducted using star-ratings given in the original reviews.
