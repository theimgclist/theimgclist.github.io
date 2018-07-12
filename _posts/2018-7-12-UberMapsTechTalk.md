---
title: Uber Maps Tech Talk
---
<p align="center"><img src="\assets\images\ubermaps.png"/></p>
<p align="center"><a href="https://rideshareapps.com/uber-fare-estimator/">Pic Credit</a></p>  

Unless you are someone who for some very mystical or other reasons have been living away from technology, you must be very used to what I call the Map Talk - "Can you share the location?", "Map's showing a lot of traffic on the way!" and other such talks. Digital and web mapping service has been one area that has continuously evolved and got better with time and technology. Though one of the reasons for that has been the advancements in technology and computation, the other main reason is that it is a very challenging and unsolved problem. And that's what makes it interesting and that's what made this Uber Maps Tech Talk very interesting too.  

Before two very informative talks we had for the day, there was a video about women in tech in Uber Bangalore's Engineering team and a trivia which had some swags for those who answered correctly. In case you are wondering, no I haven't won any! It was Ankit, Group Product Manager for Maps team who gave the first talk. In an earlier talk that happened a few months ago, the presenters explained the number of events and operations between user opening the Uber app and the end of the ride. Ankit took us through each step, starting with estimation of user localtion, searching places and addresses, calculating fares and ETA prediction. When a user opens the app, the first thing that's needed is his/her location. This involves a lot of features to consider like whether the user is indoors or outside, if the user is in a building somewhere above ground level or other such scenarios. This is done using GPS, location prediction models and WiFi fingerprinting. All of this to get that small blue dot at the right place on Uber maps!  

There are many factors that should be considered in order to facilitate searching for places or addresses for drop location. The map can use the historical data of the user(if any), show popular places with accurate locations, show a snap of Uber rides that are nearby etc. And when it comes to Uber Eats there are additional different cases that should be considered. The next step which is the fare calculation has to be very accurate. Estimated time of travel, the distance it includes, the presence of tolls, the supply of Uber rides around the current user location and also the demand for rides at the moment are determining factors of estimated fare. If this sounds complex, think about how it can vary for different types of rides - UberGo, UberPool and the more recent ExpressPool. While both UberPool and ExpressPool allow ride sharing, ExpressPool provides a ride from the nearest pickup point which the rider can take by walking to the location. This not only helps the rider to reach a location where rides are available but is also cheaper.   

<p align="center"><img src="\assets\images\expresspool.gif?raw=true"/></p>
<p align="center"><a href="https://www.uber.com/newsroom/expresspool/">Pic Credit</a></p> 

Each step builds on top of the one before it and has some extra layer of complexity. ETA prediction is the next step and it is different for different modes of ride. For UberGo/UberPool, there would be a single ETA of the driver to reach the rider. In case of express pool, the time the rider would take to reach the pickup point should also be considered. ETA calculation has few challenges. What if there is an unforeseen change in traffic? Or a sudden road block? What if the driver has a spotty network? The first two lead to recalculation of ETA. To handle spotty networks, the cached routes are reused at the driver's side. So even if the driver loses connection, there are ways to make the maps work without it. Once the ride starts, there is continuous route optimisation that happens in the background to assist the driver to take the best possible route to the destination. Historical route records of both the rider and the routes being taken are used for this purpose.  

 






