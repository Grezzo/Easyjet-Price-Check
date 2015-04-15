# easyJet-Price-Check
Checks easyJet's website for specific return flight prices and sends a push notification via prowl if cheaper.

## Description
This allows you to claim back the difference if price drops since you book the flight. [See this article on MSE](http://www.moneysavingexpert.com/travel/cheap-flights#Easyjetprice).

## Usage
You'll need to edit GetPrices to include the Departure/Return flight details (Airports, Date, Time, Price, Passengers) and to include your prowl API key (which you must set up in advance with prowl). You'll obviously also need to make the script executable.

You'll also need to make your system run the script regularly, e.g. cron on linux or launchd on OSX. I used [LanuchControl](http://www.soma-zone.com/LaunchControl/) to set it up on OSX.
