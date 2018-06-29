[![Visit our website](https://s31.postimg.org/9n8vhzwqj/datata.png)](http://links.datata.mx/datata-website)
[![Send us an email!](https://s31.postimg.org/xpo23w8yj/email.png)](mailto:contact@datata.mx)
[![Follow our blog!](https://s32.postimg.org/6l5f28pad/rss.png)](http://links.datata.mx/datata-blog)
[![See our work in GitHub!](https://s32.postimg.org/aan6j9vyd/github.png)](http://links.datata.mx/datata-github)
[![Like us on Facebook!](https://s32.postimg.org/b2lxxj2o5/facebook.png)](http://links.datata.mx/datata-fb)
[![Follow us on Twitter!](https://s31.postimg.org/8trwvjzyz/twitter.png)](http://links.datata.mx/datata-tw)
[![Follow us on LinkedIn!](https://s32.postimg.org/zeaaws26d/linkedin.png)](http://links.datata.mx/datata-linkedin)
[![Follow us in YouTube!](https://s31.postimg.org/f2navtpzf/youtube.png)](http://links.datata.mx/datata-youtube)

Contact us! We're always happy to solve complex problems!

---

# Datatón's winner project

With this project we won the national Data Science contest "Datatón" 2014 organized by the Presidential Office in Mexico. It was developed by [Omar Trejo](http://links.datata.mx/linkedin-omar-trejo) and [Luis Manuel Román](https://github.com/lromang) during a two weak period in June 2014.

## General ideas

All of the results were produced for the Zapopan area in Jalisco because the data provided in the contest was specifically for that geographic zone. There are two main ideas:

- Crime prediction using establishment data
- Real time response to events using Twitter

## Crime prediction using establishment data

We analyzed various socio-economical variables that were available in the datasets available for the contest, such as schools, shopping centers, hospitals, and others, and we used [_stochastic gradient boosting_](https://en.wikipedia.org/wiki/Gradient_boosting) to learn what characteristics lead to crime. All these observations came with an addresses that we used to find out geographical coordinates and then used to map our results.

![Map of crimes and places in the Zapopan area](http://s4.postimg.org/tkadl5a25/Screen_Shot_2014_09_12_at_1_31_02_AM.png)

## Real time response to events using Twitter

We developed a system that analyses a Twitter feed produced in a geographical zone (in this case Zapopan) and look for words that are linked to crime, such as _robaron_, _dispararon_ and _mataron_ (stole, shot and killed) and then potentially provide those people with an automatic response that informs them of the closest hospital available, the route and the phone number. The route provided is optimal and it is taken through the [Google Directions API](https://developers.google.com/maps/documentation/directions/) so that it incorporates traffic status.

![Map of gas stations and keywords in Mexico City](http://s30.postimg.org/8sfljqbxt/Mexico_City.png)

## Further information

These are the [slides](http://links.datata.mx/dataton-slides) we presented at [Instituto Tecnológico Autónomo de México (ITAM)](http://www.itam.mx) and [Universidad Panamericana (UP)](http://www.up.edu.mx/es) about our project.

![Datatón slides](https://s31.postimg.org/lb4hvf4y3/dataton_slides.png)

This is the [document](http://links.datata.mx/dataton-document) we presented in the _Datatón_ contest. It had a word limit so we couldn't present all of the information or technical details we would have liked and the technical explanations were limited.

![Datatón document](https://s32.postimg.org/gjbrs1qw5/dataton_paper.png)

Any feedback is welcome!

---

As always, have fun learning something new!
