# Brewzinga!

Brewzinga! is a web application that recommends beers based on an event or the user's local weather using Weather Underground API and BreweryDB API. It's a single-page app that also displays local breweries using AJAX and jQuery.

Link to website deployed site: [http://brewzinga.surge.sh/](http://brewzinga.surge.sh/)

![alt text](https://github.com/bradefting/Brewzinga/blob/master/img/Brewzinga-readMe.jpg)

### Features

1. **Weather search** Allows a user to receive beer recommendations based on their local weather. Simply enter a 5-digit zip code and the Weather Underground API will provide the weather condition and temperature for the zip code. Then, three styles of beer are recommended based on the weather temperature. Select a style and the BreweryAPI will provide three beers matching that style. Select a beer from the results and a short description of the beer is provided and brewery its brewed at.
2. **Event search** Have a special event you want to attend but don't know what beer to bring? Brewzinga! can help you decide. Simply select an event from the dropdown and the BreweryDB API will provide three recommended styles. Select one of the styles and three recommended beers of that style are shown. Select a beer from the results and a short description of the beer is provided and brewery its brewed at.   
3. **Find a local brewery** Want to enjoy a beer with others at a pub or brewery? Brewzinga! can find local breweries if you enter your 5-digit zip code. If no results are found, that simply means your local establishments haven't registered on the BreweryDB API or you're in a pretty lame area.

### Technologies

1. **Weather Underground API:** An API used to retrieve weather conditions.
2. **BreweryDB API:** An API used to provide all beer and brewery information.
3. **Materialize:** Used to create the front-end design.
4. **jQuery:** Used for functionality of the application.
5. **Surge:** Used to deploy the application.

Video walkthrough of the app: [https://www.youtube.com/watch?v=aJO_bQ4lRUc](https://www.youtube.com/watch?v=aJO_bQ4lRUc)
