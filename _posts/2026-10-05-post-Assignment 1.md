---
title: "Assignment 1"
categories:
  - Blog
header:
teaser: /assets/images/chile.jpg
tags:
  - assignment
---

# Background & Expectations


This essay explores the location of my birth and upbringing, Chile. I did this through open-sourced data on GeoNames. I had assumed that I would find regular data on locations associated with my past daily life back in Chile. Such as schools, malls, governmental, and retail buildings in downtown Santiago. However, I found most of the locations tagged in the GeoNames dataset mainly associated with the countryside. There were 207 ranches, and only 5 schools were recorded. I found myself unfamiliar with this new territory of data in my country. Fortunately, I did not give up, as I believed those 46467 rows of data would eventually show something worth investigating. I explored the various columns and tried out different tags in Posit Cloud. After I generated many maps using the most popular tags, I wondered: How can I make such an abundant amount of data in ranches, springs, and mountains interesting? I found my answer through my childhood memories of leaving the capital and exploring the rest of Chile myself. 

How do Chileans move around in such a long country? Mostly through buses and airplanes, and some trains. As a child, I remember my dad making a point out of taking two of the non-recurring remaining operating trains out of Santiago: one towards Chillán to visit the thermal waters near the Andes, and the other towards San Antonio to visit the beach, both locations still in the relative centre of the country. But this was not something common. On a different occasion, we took the bus from the capital towards the deeper south. We spent over 12 hours on a bus, going all the way from Santiago to Puerto Montt. We got around the towns in the vicinity through taxis and then got a flight back to Santiago from Temuco. Transportation in Chile had an intentional meaning to me. Thus, I decided to see what the GeoNames data had to say about it.

# Computational Insights

The GeoNames data misrepresents the reality of the transportation scene in Chile. Their dataset recorded 227 airports/airdomes, 415 railroad stations, and 4 bus stations. In reality, all of these figures are inaccurate and severely outdated in the case of railroads.

<iframe src="{{ site.baseurl }}/assets/maps/Assignment1 - Posit Cloud.html"
width="100%"
height="600px"
style="border:none;">
</iframe>

## Figure 1: Chilean Transportation Modes

A hundred years ago, Chile had a successful railroad ecosystem with hundreds of stations and millions of passengers. Past the 1970s, the Chilean rail industry was unable to survive without governmental support. As a result, most of the railroads closed down (colaboradores de Wikipedia, 2026). The country currently has 11 active railway pathways run by EFE Trenes de Chile with less than 120 railroad stations; 8 of these networks focused on the relative centre and outskirts of the capital, and none extended to the north or had a continuous connection from centre to south (Tren Rancagua – Estación Central – Servicio Y Trazado, n.d.). Besides, there are some trains of touristic nature, only running a few times per year (Claro, 2026). But the subway system inside the capital, Santiago, and its outskirts is highly active. Surprisingly, the GeoNames railroad station data omitted Santiago's active metro stations. Instead, it mostly, if not entirely, mapped dead train stations. Such as Concordia in the deep south, which closed in 1990 (colaboradores de Wikipedia, 2025). I found this was the case for many of the stations from the GeoNames dataset, which were either demolished or abandoned.

In the case of airports/airdomes, the GeoNames data on 227 of these is still prevalent. However, more have been added in recent years. The Chilean Directorate General of Civil Aviation states the nation hosts 310 airdromes and 7 airports (Dir. General Aeronáutica Civil, 2025). Unlike the case with trains, the airports/airdomes in the dataset exist in the present. Still, the GeoNames data could use some updates and additions.

Furthermore, the GeoNames data on buses is nearly non-existent, with only 4 bus stations recorded in their system. Reality juxtaposes this, with public bus stations by themselves amounting to 11,990 in Chile (colaboradores de Wikipedia, 2026b). With the contrast of airport data presented by GeoNames being up to date and accurate for the most part. I raise the question: Why is airport data better recorded in GeoNames than bus or train station data? Considering Kitchin and Lauriault's (2017) ideas in "Toward Critical Data Studies," we should question data and the fact that it does not arise from nowhere (p. 6). While airports are more modern than trains and buses, the dataset itself has gone through major updates in 2013, 2016, and 2018. And with a Chilean ambassador in GeoNames, it is hard to believe it is not an intentional choice to keep the archaic train data. Does the stagnant railway data come from nostalgia? Or disinterest and neglect? After all, airports, springs, mountains, ranches, and hotels have the most records in the dataset. With barely anything useful to someone experiencing daily life and its nuances in Chile. My conclusion is that the GeoNames information is directed towards non-Chileans planning a touristic trip to Chile.


# Methodological Questions

The provenance of the data in GeoNames comes from reputable national governmental sources such as the Subsecretary of Regional and Administrative Development, National Institute of Statistics, and Ministry of National Assets. Therefore, there is a possibility that the misrepresentation of the transport scene in Chile is enabled by the non-updated data from national sources. However, the ambassadors/mapmakers of GeoNames should also be held accountable. They are responsible for assessing the data they portray to the world and possibly finding other alternatives and sources to inform their repository.

The Chilean transportation case of GeoNames I have presented can be used as an example of mishandled open data activism. Kitchin & Lauriault (2017) express that the open data movement made government data more accessible for people (p. 5). GeoNames is part of this movement and uses data coming from Chilean repositories to allow people to freely explore it. However, as no data is unbiased, GeoNames is partly responsible for putting this information out to the best of their knowledge. Especially, as map data gives them power and their output, regardless of the preliminary data in hand, adds on to their inherent bias. As Shiloh Krupar (2015) states in Map Power and Map Methodologies for Social Justice, “Maps are efficient modes of communication with a strong hold on people's imaginations.” (p. 91). GeoNames has the power to re-shape how transportation looks in Chile for outsiders and insiders.

For further investigation, understanding how GeoNames processed the data presented by Chilean governmental sources would be essential for understanding the biases the GeoNames team holds. My main questions surround whether it is the GeoNames team that has such archaic data on transport in Chile or whether the government has not updated their records and that’s what they were given. Not only that, but do GeoNames strictly present the data given, or do they only filter the information depending on their interests? Take for example, outside the realm of transportation; did the lack of data on institutions other than tourist ones come from national sources, or was this cut out by the GeoNames team? 

# Transferability

Mapping is a new language for me that allows for my ideas to go further. Communicating structural problems is not always easy, especially in words. Maps solve this problem and make complex ideas accessible. As a political science major in my final year, this can be fundamental if I go into governmental work. For example, this project on transportation in Chile made me realize EFE Trenes de Chile (Chilean National Railway)’s lack of visualization of their train routes on their website can be confusing. If they ever wanted to push forward and collaborate with any organizations to lobby for reinstating a railway connecting the capital to the deep south, they would first need to visualize their past and current rail stations. In that manner, citizens and organizations can visualize the impact such projects would have on their surroundings, rather than just hearing imaginary words and numbers.

## Generative AI Statement

I used Claude throughout this assignment for minor improvements and troubleshooting for my PositCloud map and Visual Studio code. I used Apple Intelligence for basic proofreading.