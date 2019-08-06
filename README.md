# Curtailment Forecast
Website displaying forecast of curtailment in the Orkney ANM

#### _What is this?_

A forecast of how likely it is that curtailment of generators will be issued in the Orkney Active Network Management system (ANM). Like a weather forecast, but just with curtailment instead. It can be used to get an overview of the next five days, and the idea is to incorporate this service with power hungry devices, to schedule the tasks for times where energy is in excess. Currently it is simply a demonstration of our models and hopefully it can help make the ANM curtailment system a little more understandable for the orcadians affected by it.

#### _How does it work?_

Through a bunch of data collection and analysis, we have created a model that estimates probability of curtailment based on wind speeds, day-of-week, and time-of-day. We then combine this model with the weather forecasts generated by the [UK Met Office](https://www.metoffice.gov.uk/weather/forecast/gftcsumwq#?date=2019-05-15) to make predictions of whether curtailment will happen at certain times in the future. The data for training the model have been collected through the [SSE's ANM website](https://www.ssen.co.uk/ANMGeneration/), and wind speed data generated by a single turbine in Orkney.

#### _Who made this?_

This website is a by-product of a MSc-thesis project by [Niels Ørbæk Christensen](mailto:niec@itu.dk) at the IT University of Copenhagen, made in collaboration with the [Orkney Cloud](http://orkneycloud.org/) project, envisioning community-led data services in Orkney.
