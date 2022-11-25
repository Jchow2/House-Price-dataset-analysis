# Expedia Hotel Searches Predictive Model 
Expedia has provided a dataset that includes shopping and purchases data. The data are organized around a set of “search result impressions”, or the ordered list of hotels that the user sees after they search for a hotel on the Expedia website. The data contain impressions where the hotels are randomly sorted to avoid the position bias of the existing algorithm. The user response is provided as a click on a hotel and/or a purchase of a hotel room.

Learning to rank hotels to maximize purchases using time series analysis and machine learning models. Load and filter dataset using the highest correlated variables to hotel prices which includes 

- prop_id (hotel id) 
- visitor_location_country_id (country id the customer is located in)
- srch_room_count (number of hotel rooms specified in search) 
- date_time (date and time of the search)
- price_usd (the displayed price of the hotel for the given search)
- srch_booking_window (number of future days the hotel stay started from the search date)
- srch_length_of_stay (number of nights stay that was searched)
- srch_saturday_night_bool (+1 if the hotel stay includes a Saturday night with a length of stay is less than or equal to 4 nights; otherwise 0)
