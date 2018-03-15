---
title: Uber Tech Talk @ Bangalore
---
![](\assets\images\uber.png?raw=true)

Last week I attended a tech talk organised by Uber and Datagiri which happened here in Bangalore. It was on Women’s Day and the venue was 91SpringBoard which provides shared coworking space. There were a lot of people who showed interest and close to 200 people turned up at the meetup. It was Divyesh, the Engineering Manager at Uber who started the talk with a welcome speech. He had previously worked at Google and started by thanking us all for showing up at the meetup. During the brief talk, Divyesh spoke about how Uber helps its drivers in multiple ways.

I had little idea about how Uber uses Analytics and Machine Learning to make better decisions with Uber rides before Sudhir’s presentation which followed after Divyesh’s. Sudhir started by saying Uber is not just a car company. It is a tech company first. This talk gave many valuable insights into how Analytics is currently being used at Uber. This is my favourite part of the entire tech talk and that’s because Sudhir made the things he was presenting very clear and understandable. And of course, there were some very cool visualizations throughout his talk. He showed us the visualization of all the trips/rides that were happening in and around Bangalore in real-time at that specific time. When he asked how many of us are already working as Data Engineers or Data Scientists only 20% raised their hands. So there were more aspiring Data Scientists.

Sudhir went on to explain how real-time Online Analytics Processing(OLAP) happens with Uber rides and the technology stack that is involved. There are close to 500 metrics like ETA, cancellation rate etc that are considered during this process. Then there was another question. How many of us use Jupyter? You must be knowing the answer. Almost all of us! Using Analytics, Uber is now able to keep its drivers well informed about where to be and when to be. Though it might seem like, San Francisco’s airport is a nice place to be to get yourself some rides if you are an Uber driver, the data says differently. It shows when it is the right time to be at the airport and when it’s not.


![](\assets\images\ubermeetup.jpg?raw=true)
<p class="caption"><i>Got these at the registration desk</i></p>

All these examples were backed up with some visualisations on real-time data. Uber pool is different from the normal rides as it needs more analysis and computation. Matching multiple riders with an Uber ride is a different game altogether. Did you know that 80% of rides that happen in SFO are pool rides? In the rest of the world, it’s 20%. There are many events that get triggered starting from when the user/rider opens the app and until the ride is finished. As part of this process, Uber uses Apache Samza, Kafka, ElasticSearch, Redis, Presto and few others as part of it’s technology stack. The best part of it is that these are all open source! When asked about what are the challenges that Uber India faced, the answer was that the payment system was one of the challenges. While the preferred mode of payment is cards in many other countries, in India they had to consider cash as the main mode of payment. “India proved Uber that cash matters!”

It was Aman Gairola’s turn next who is a Senior Data Scientist at Uber and is part of AdTech team. What is AdTech? To put it simply, Ad tech is a set of methodologies that deliver the right content at the right time to the right consumers. And if you have a tech company like Uber that uses multiple channels or platforms for marketing/advertisements, you would surely want to know which of your marketing partners are responsible for the new user/s that the company has made. This is called attribution. This may not be as easy as it seems, especially with challenges such as — how to figure out what channel led to the conversion of a new user? In case of multiple channels, how do we attribute to the correct channel? If you had an ad campaign on Facebook, Google Search, TV ad etc, how will the attribution be made? Aman showed few methods for achieving this. One more thing worth mentioning is that, when an ad campaign is run which involves a considerable amount of money, it’s important to have an ad-fraud detection mechanism so that you don’t end up paying for fake clicks.

<p align="center"><img src="\assets\images\datacleaning.jpg?raw=true" alt="" /></p>
<p class="caption"><i>Pic Credit : Pinterest</i></p>

Pramod Biligiri, a Data Engineer at Uber who also works on AdTech related products shared his experiences as a Data Engineer. As a Data Engineer, one should make sure the data is organised and is made available at the right time. No matter how much data is available, it’s of no value if no insights can be drawn from the data. He says, as a Data Engineer or doing any task that deals with data, one should know the right questions to ask as this often leads to insightful analysis. Missing data should be handled properly so that it doesn’t lead to wrong conclusions. Making use of the existing libraries should be preferred to reinventing the wheel and building something from scratch when it’s not necessary. What about data privacy? Sensitive data is anonymized before doing any kind of analysis on it and data is retained only for a few days or some agreed upon time.

With so much to learn from the internet resources on Machine Learning and Data Science, it is this kind of sessions that help in knowing how they are actually implemented and used in real-time. We got to talk to all of the speakers and also few others from Uber who helped us with our questions. There was a lot to learn from this meetup that lasted for more than a couple of hours. If you liked what you read so far in this article and would like to follow what’s all happening at Uber, I recommend checking [this](https://eng.uber.com/) blog from Uber and also following [@ubereng](https://twitter.com/UberEng) on Twitter.


> Big thanks to Mayuresh Shilotri from DataGiri and Uber for organizing this meetup. If you liked this post, dont shy away from heading over [here](https://medium.com/@theimgclist/google-knows-how-to-teach-45e531ab3ada) and give it a clap(or two :wink: ). Thanks for reading!!




