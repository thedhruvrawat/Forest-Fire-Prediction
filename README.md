<p align="center"> <img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/d3/BITS_Pilani-Logo.svg/1200px-BITS_Pilani-Logo.svg.png" height=150></p>

# Predicting the area burnt by forest fires in the northeast region of Portugal

![Language](https://img.shields.io/static/v1?label=Language&message=Python&color=brightgreen&style=for-the-badge)
&nbsp;
![Platform](https://img.shields.io/static/v1?label=Platform&message=Anaconda&color=informational&style=for-the-badge)
&nbsp;
![Contributers](https://img.shields.io/static/v1?label=Contributers&message=4&color=important&style=for-the-badge)

Course Assignment for <b>ECON F241: Econometric Methods</b>

The assignment report can be accessed here: `Contact authors for link`
<hr>

### Group No. 5
- <b>Dhruv Rawat (2019B3A70537P)
- Sujay Patni (2019B3A70575P)
- Ram Mehta (2019B3A80510P)
- Nikunj Mehadia (2019B3A70343P)</b>

<hr>

## Abstract
We will be creating a model to predict the burned area of forest fires, in the northeast region of Portugal, by using meteorological and other data. Our aim is to predict the burned area (hectares) of forest fires. Based on the the spatial, temporal, and weather variables where the fire is spotted. This prediction can be used for calculating the forces sent to the incident and deciding the urgency of the situation.
Our model has been regressed by the method of Ordinary Least Squares (OLS). The variables used are - 
1. `FFMC` - FFMC index from the FWI system
2. `DMC` - DMC index from the FWI system
3. `DC` - DC index from the FWI system,
4. `ISI` - ISI index from the FWI system
5. `temp` - temperature in Celsius degrees
6. `RH` - relative humidity in %
7. `wind` - wind speed in $km/h$
8. `rain` - outside rain in $mm$/$m^2$
9. `area` - the burned area of the forest (in ha)

## Directories
- [dataset](dataset) contains the .csv files containing all metereological data.

- [notebook](dataset) contains the Jupyter Notebook which has the code of our model

## License
[MIT](https://choosealicense.com/licenses/mit/)