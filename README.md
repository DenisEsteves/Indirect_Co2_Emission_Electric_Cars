## 🚗 🚗 🚗 Indirect Co2 emission of electric cars 🚗 🚗 🚗

The impact of the ecology in society consuming habits is more and more important. One of the industries where the change is more obvious and bigger is the car industry: new motors, new materials... new business models. 

However, do consumers really know how much they will pollute if they decide to buy an electric car? Are they aware that even if the electrical car engine does not directly emit Co2 to the environment, those cars pollute? Can this pollution be compared with the emission of diesel cars?

The idea behind this project is to give the car buyers an estimation of greenhouse gases (Co2) of different cars depending on the countries they are driven.

## Methodology:

First, I downloaded a car database of 43000 cars (electric and combustion) from [Fuel economy](https://www.fueleconomy.gov/).
 
Using the API of the World Bank, I downloaded the electricity source breakdown of every country in the world. 

Then, I created functions to calculate for every electric car which would be the Co2 emissions in a given country taking into account the electricity source breakdown of the country and their drive habits.

Thereby, it is possible to compare the greenhouse emission, calculated as Co2 grams per kilometer, between different cars no matter the type of the motor. 
