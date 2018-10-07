
![Image of WeatherOrNot](https://github.com/shauryr/WeatherOrNot/blob/master/weatherornot.png)

## Inspiration
* Everyone has a bucketlist of places they want to visit. They just can't figure when is the best time to go. 
* Even if they find that they find it difficult to get the best deals. 

We ourselves love to travel and we are from a small country where the weather is predictable and doesn't change much. We are not used to checking the weather before travelling. We just look outside and leave the house or book tickets. 

**What if while booking tickets we could get smart suggestions of where to go next on the basis of the best weather conditions and the cheapest flight tickets for places in your bucketlist!**

## What it does
* It scraps trip adviser to get the best weather condition for that place
* It scraps Google Flights for Flight information
* It queries AccuWeather's api to get the forecast of the next 15 days
* Does some magic ! and BOOM you are presented with a sorted list of places with the best weather and cheapest tickets

## How we built it
We built it using python scrapers - beautiful soup. The website framework used is flask. The UI framework is Bootstrap. The backend is mostly python code.

## Challenges we ran into
* Flights API are not free ! Skyscanner works with companies to get that data to you. But they take a lot of time to process and you are contacted by there representative. So, we just scraped the data for particular dates.
* Dynamically getting weather data is possible but getting flight details is not. You require special access to do that for particular dates



## Accomplishments that we're proud of
* Our core algorithm works pretty well and the suggestions do make sense !
* We were able to find workarounds by scraping the web
* It saves you time. Just with simple clicks you can get something which earlier took a lot of time and effort 
* Choosing from a list of things makes the bucketlist truely personal which we appreciate a lot
* We get the best weather according to that place ! The "best" is dynamic and depends on the place.

## What we learned
* Getting flight booking details is tough !
* Weather can make or break your vacation


## What's next for WeatherOrNot
* We would like to do it for further dates as well using the past years predictions
* Partner with flight booking websites to get richer flight details
* Add activities to the interface ! If it is sunny go for a hike/ go to the beach ! The users can define what they want to do and we can suggest the place
