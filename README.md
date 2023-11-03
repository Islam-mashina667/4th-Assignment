# 4th-Assignment
4th assingment in the course INF-201


When you will run the code, you should see the output on the console, which will include the standardized weather data and the source format. In the example provided, it will show the standardized weather data in JSON format.

Let's understand how the code works:

WeatherData Class: This class defines the common data model for weather data. It has fields for temperature, humidity, wind speed, and condition, along with a constructor to initialize these fields.

WeatherDataAdapter Class: This class is the adapter responsible for translating data from different weather APIs into the standardized format. It takes the raw data in the form of a Map and the source format as input. The getStandardizedWeatherData method extracts the relevant data fields (temperature, humidity, wind speed, condition) from the raw data and creates an instance of the WeatherData class. The getSourceFormat method returns the source format. This class allows you to work with different data formats by creating instances for each source.

Main Method: In the main method, we provide an example of using the adapter for JSON data. We create a WeatherDataAdapter instance with JSON data and then extract and print the standardized weather data along with the source format. This showcases how you can use the adapter to work with various data sources.

In a real application, you would create instances of the WeatherDataAdapter class for different data sources (e.g., XML, CSV, API responses), extract standardized data using the getStandardizedWeatherData method, and use this data to display weather information consistently in your mobile application, regardless of the source 
