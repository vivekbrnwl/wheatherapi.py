# wheatherapi.py
Read Me:

https://samples.openweathermap.org/data/2.5/forecast/hourly?q=London,us&appid=b6907d289e10d714a6e88b30761fae22

The above API is the REST GET API Which gives you the response in JSON format and hourly weather forecast of London Location

Automating the below test cases for all the available data

1. Is the response contains 4 days of data
2. Is all the forecast in the hourly interval ( no hour should be missed )
3. For all 4 days, the temp should not be less than temp_min and not more than temp_max
4. If the weather id is 500, the description should be light rain
5. If the weather id is 800, the description should be a clear sky
