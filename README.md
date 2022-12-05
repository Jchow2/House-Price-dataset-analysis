# Expedia Hotel Searches Predictive Model 
Expedia has provided a dataset that includes shopping and purchases data. The data are organized around a set of “search result impressions”, or the ordered list of hotels that the user sees after they search for a hotel on the Expedia website. The data contain impressions where the hotels are randomly sorted to avoid the position bias of the existing algorithm. The user response is provided as a click on a hotel and/or a purchase of a hotel room.

## Why is this important?
Predicting hotel prices to identify user purchasing habits and to determine whether the price advertised on Expedia is over or under-estimated, booking searches result in the most affordable prices, etc.
 
## What is the objective of the machine learning model(s)?
Learning to rank hotels to maximize purchases using forecasting and machine learning models. Load, filter, and subset a dataset with these variables:
- prop_id (hotel id)
- visitor_location_country_id (country id the customer is in)
- srch_room_count (number of hotel rooms specified in search)
- date_time (date and time of user search)
- price_usd (the displayed price of the hotel for the given search)
- srch_booking_window (number of future days the hotel stay started from the search date)
- srch_length_of_stay (number of nights stay that users searched)
- srch_saturday_night_bool (+1 if the hotel stay includes a Saturday night with a length of stay less than or equal to 4 nights; 0 if otherwise)

## Data Set Description
Expedia has provided a dataset that includes shopping and purchases data. The dataset of “search result impressions” of an ordered list of hotels on the Expedia website. The data contain impressions where the randomly sorted hotels avoid position bias. The user response is a click on a hotel or a purchased hotel room. 

### The project aims to build a machine learning model to predict the booking price of a hotel based on different explanatory variables describing the Expedia search engine and consumer preferences.
