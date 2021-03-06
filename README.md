# Building a weather app... with React!!

Ever made a weather app using APIs? Ever made a weather app using APIs... _with React?_

## Setting up

#### 🚀 Make sure you follow all of these steps!

1. Sign up for a free [Open Weather Map](https://home.openweathermap.org/users/sign_up) account!
2. Once you've signed up, you're given an [API key](https://home.openweathermap.org/api_keys). Copy that API key and keep track of it somewhere!
3. Open Postman to check out the data you're working with & to verify that your key works. Make a GET request to the following URL in postman, adding your API key to the end.
4. Read the [API documentation](https://openweathermap.org/current) carefully, to make sure you know how to make each request!

```
http://api.openweathermap.org/data/2.5/weather?q=10025,us&units=imperial&appid=[YOUR API KEY HERE]
```

#### Use `create-react-app` to get started. The name of the app is up to you.

## In the end, your weather app will look like this in the mobile view:

![mockup](https://media.git.generalassemb.ly/user/4451/files/c61d4a80-d30f-11ea-95de-dba5488d2402)

## Your page should have:
- An input field for a user to enter a zip code
- A submit button
- When the submit button is clicked:
    - A GET request should fetch the weather data from the API
    - The following data should be rendered on the page:
        - City name
        - Current temperature
        - Weather description
        - Min temp
        - Max temp

Here are some zip codes to test!
- 99501 (Anchorage)
- 99723 (Barrow, AK)
- 60605 (Chicago)
- 70124 (New Orleans)
- 77030 (Houston, TX)
- 00902 (San Juan, Puerto Rico)
- 46923 (Delphi, IN)
- 94123 (San Francisco, CA)


## BONUSES!!

- Have the temperature turn blue if under 40, and red if above 90.
- Add the latitude and longitude, humidity, precipitation, and wind speed
- Add sunrise and sunset times (look into [the javascript date object](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date)... if you dare!!!)
- Get the desktop view to work like this:

![desktop](https://media.git.generalassemb.ly/user/4451/files/59568000-d310-11ea-834b-391449a06b4e)
