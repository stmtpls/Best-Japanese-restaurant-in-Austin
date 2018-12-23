# Yelp Reviews - Finding the best Japanese restaurant in Austin

## TL;DR

Scrapping data of restaurant reviews (restaurant - review - star rating) I performed sentiment analysis and used cosine similarity to identify the top three restaurants in the Austin, TX area in terms of:

- Service
- Food
- Price
- Location

And then compared them with the website's current rating method, using the average star rating.

Performing lift and sentiment analysis regarding the identified issues for both candidates we concluded the following:

All the steps of the process are thoroughly presented in the project's report.

## Tools used

- Python 3
- Jupyter Notebook
- Vader 
- Sklean


## Key take-away

- If you like Japanese food and live in Austin you should try: 

1. Haru Sushi - formerly known Hanabi
2. Sushi Junai 2
3. Ramen Tatsu-Ya

## Interesting Insights

- Restaurants which are highly rated in terms of the attributes on the basis of which the user is seeking recommendation, appears at a lower rank when listed solely based on ratings. Therefore, simply building the recommendation system on user ratings does not meet the requirements of the user looking for recommendations.

- The restaurant 'Haru Sushi - formerly known Hanabi' is the most desirable restaurant in terms of the user mentioned attributes. However, it is ranked 9th in terms of ratings and far behind restaurants which are barely mentioned when the four attributes (Service, Food, Price,Location) are discussed in the reviews.

- Based on the ratings, the best japanese restaurant is "Baja St Tacos & Coastal Cuisine" which is not a traditional japanese restaurant and while it is highly rated by people that like the combination of tex-mex and japanese cuzine, it is not highly correlated to japanese "food" and as a result it may not be suitable for people looking for japanese flavors.

- The list of 200 reviews with the highest cosine similarity includes no review of the "top three based on ratings" restaurants, which indicates that while those restaurants get positive feedback same is not strongly correlated to the four identifed aspects and as a result they do not present a good value proposition.


## Yelp suggestions - Areas of improvement

The website's recommendation system would be much improved incorporating rastaurant type specific aspects and features to the search engine (e.g. Service, Food, Price, Location) helping users find exactly what they are looking for.
