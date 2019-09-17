# BikeRentingProject
The objective of this Case is to Predication of bike rental count on daily based on the environmental and seasonal settings. 

# PROBLEM STATEMENT
The objective of this project is to predict of bike rental count on daily based on the environmental and seasonal condition or settings. The given dataset has 731 observations and 16 variables in that 15 predictors and 1 target variable. The 15 predictors are the various environmental and seasonal factors like season, humidity, temperature etc. So we need to build a production-ready prediction model that predict the estimate count or demand of bikes on a particular day based on environmental and season condition

# DATA
- instant     : Record index
- dteday      : Date
- season      : Season (1:springer, 2:summer, 3:fall, 4:winter)
- yr          : Year (0: 2011, 1:2012)
- mnth        : Month (1 to 12)
- hr          : Hour (0 to 23)
- holiday     : weather day is holiday or not (extracted fromHoliday Schedule)
- weekday     : Day of the week
- workingday  : If day is neither weekend nor holiday is 1, otherwise is 0.
- weathersit  : (extracted fromFreemeteo)1: Clear, Few clouds, Partly cloudy, Partly cloudy 2: Mist + Cloudy, Mist + Broken clouds, Mist +                    Few clouds, Mist 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 4: Heavy                        Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp        : Normalized temperature in Celsius. The values are derived via (t-t_min)/(t_max-t_min), t_min=-8, t_max=+39 (only in hourly                    scale)
- atemp       : Normalized feeling temperature in Celsius. The values are derived via (t-t_min)/(t_maxt_min), t_min=-16, t_max=+50 (only in                   hourly scale)
- hum         : Normalized humidity. The values are divided to 100 (max)
- windspeed   : Normalized wind speed. The values are divided to 67 (max)
- casual      : count of casual users
- registered  : count of registered users
- cnt         : count of total rental bikes including both casual and registered
