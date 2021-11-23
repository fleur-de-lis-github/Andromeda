# Andromeda

##Problem Scenario

Smaller asteroids that are believed to strike Earth every 1,000 to 10,000 years could destroy a city or cause devastating tsunamis. According to NASA, space rocks smaller than 82 feet (25 m) will most likely burn up as they enter Earth's atmosphere.

"Greenhouse gases block about 40 percent of outgoing thermal radiation that emanates from Earth," Woods said. The resulting imbalance between incoming solar radiation and outgoing thermal radiation will likely cause Earth to heat up over the next century, accelerating the melting polar ice caps, causing sea levels to rise and increasing the probability of more violent global weather patterns.

## Our Approach
``` diff
+ As far as, asteroids are concerned, there are many asteroids called near-earth asteroids, but all are not hazardous. So, our target
+ in this paper is to identify those hazardous asteroids and classify them with non-hazardous types. For this, I choose many machine
+ learning models. I trained those various model with the data features and later I compare those results to find the most accurate
+ model which gives the most accurate classification.

- The global solar radiation forecasting can be performed by several methods; the two big categories are the cloud imagery combined with
- physical models, and the machine learning models. In this context, the objective of this paper is to give an overview of forecasting methods
- of solar irradiation using machine learning approaches.
```

## Business Client

NASA intends to launch a series of spacecraft that would measure fundamental aspects of global warming. The report estimated that the necessary missions might cost between US$300 million and $800 million apiece, and suggested that they might be doable even with tight budgets. `In April, Biden proposed boosting NASA’s Earth-sciences budget to nearly $2.3 billion` :fax: https://www.nature.com/articles/d41586-021-01230-5
Solar Radiation            |  Hazardous Asteroid
:-------------------------:|:-------------------------:
![](https://64.media.tumblr.com/7ba8c1efa6b61e8eb9619db53c975312/tumblr_ptuey8YByw1snyofqo1_500.gifv)  |  ![](https://c.tenor.com/hzS9RwFM4yAAAAAd/crashing-to-earth-meteor-showers101.gif)

## Data Description
:earth_africa:The data is about Asteroids - NeoWs.
NeoWs (Near Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NeoWs a user can: search for Asteroids based on their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall data-set.

All the data is from the (http://neo.jpl.nasa.gov/).

:earth_africa:The Irradiance dataset contains such columns as: "wind direction", "wind speed", "humidity" and temperature. The response parameter that is to be predicted is: "Solar_radiation". It contains measurements for the past 4 months and you have to predict the level of solar radiation.

## Citation
- http://dspace.univ-msila.dz:8080/xmlui/handle/123456789/21036
- https://ieeexplore.ieee.org/abstract/document/8891934
- https://ieeexplore.ieee.org/document/7106780
