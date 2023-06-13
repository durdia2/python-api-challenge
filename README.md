# python-api-challenge
    in this python api challenge:
    Part 1
    
    To fulfill the first requirement of this challenge, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

        Latitude vs. Temperature

        Latitude vs. Humidity

        Latitude vs. Cloudiness

        Latitude vs. Wind Speed
        
    To fulfill the second requirement of this challenge, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):
        You should create the following plots:

        Northern Hemisphere: Temperature vs. Latitude

        Southern Hemisphere: Temperature vs. Latitude

        Northern Hemisphere: Humidity vs. Latitude

        Southern Hemisphere: Humidity vs. Latitude

        Northern Hemisphere: Cloudiness vs. Latitude

        Southern Hemisphere: Cloudiness vs. Latitude

        Northern Hemisphere: Wind Speed vs. Latitude

        Southern Hemisphere: Wind Speed vs. Latitude
        
    Part 2: VacationPy
    In this deliverable, you'll use your weather data skills to plan future vacations. Also, you'll use Jupyter notebooks, the geoViews Python library, and the Geoapify API.
        1.Create a map that displays a point for every city in the city_data_df DataFram
        2.Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

       - A max temperature lower than 27 degrees but higher than 21

        - Wind speed less than 4.5 m/s

        - Zero cloudiness
        
        3.Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

        4.For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

        5. Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image:




