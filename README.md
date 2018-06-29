
# Datatón's winner project

With this project we won the national Data Science contest "Datatón" 2014
organized by the Presidential Office in Mexico. It was developed by [Omar
Trejo](http://links.datata.mx/linkedin-omar-trejo) and [Luis Manuel
Román](https://github.com/lromang) during a two weak period in June 2014.

## General ideas

All of the results were produced for the Zapopan area in Jalisco because the
data provided in the contest was specifically for that geographic zone. There
are two main ideas:

- Crime prediction using establishment data
- Real time response to events using Twitter

## Crime prediction using establishment data

We analyzed various socio-economical variables that were available in the
datasets available for the contest, such as schools, shopping centers,
hospitals, and others, and we used [_stochastic gradient
boosting_](https://en.wikipedia.org/wiki/Gradient_boosting) to learn what
characteristics lead to crime. All these observations came with an addresses
that we used to find out geographical coordinates and then used to map our
results.

## Real time response to events using Twitter

We developed a system that analyses a Twitter feed produced in a geographical
zone (in this case Zapopan) and look for words that are linked to crime, such as
_robaron_, _dispararon_ and _mataron_ (stole, shot and killed) and then
potentially provide those people with an automatic response that informs them of
the closest hospital available, the route and the phone number. The route
provided is optimal and it is taken through the [Google Directions
API](https://developers.google.com/maps/documentation/directions/) so that it
incorporates traffic status.
