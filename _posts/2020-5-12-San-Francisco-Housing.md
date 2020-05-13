---
layout: post
title: Permits and Evictions in San Francisco Neighborhoods
---
### Is there any correlation between neighborhoods with higher eviction rates and divestment?



It is known that the Bay Area in general has been rapidly developing with a tech boom in the past 20 years or so. What started mostly in San Francisco has spread to a rise in cost of living all throughout the Bay Area, making San Francisco specifically now the most expensive city in the US. This means a large number of new permits for development in the city in response to a massive influx of “outsiders” as any SF born and raised individual could tell you. However, what is not always touched upon as well when looking at the development of SF is the rate of peoples being displaced. San Francisco is notorious for having a large number of individuals experiencing homeslessness and there is a lot of talk around how this is related to the tech boom, rapid development pricing people out, displacement and gentrification. One of key tools that allows for these things is evictions. Therefore, it is worth exploring the intersection of data around permits in SF and data around evictions in SF to see if there are consistencies with neighborhoods that face massive rates of eviction as well as divestment. 
 
  
The data used for these analyses was data taken from [DataSF](https://datasf.org). There were two datasets we focused on. The first was [Building Permits](https://data.sfgov.org/Housing-and-Buildings/Building-Permits/i98e-djp9), and the second was [Total eviction notices by year since 1997](https://data.sfgov.org/Housing-and-Buildings/Eviction-Notices/5cei-gny5). The building permits dataset contains decades of information, however we only look at data starting around 2000 to present day. It is a pretty boring dataset that goes through the logistical details of each building permit around things like estimated cost, revised cost, number of stories etc. The evictions dataset goes through details like the type of eviction, when it was filed, the address of the residence it was filed at, etc. Because both datasets were collected by the city, how the neighborhoods are defined in terms of boundaries is consistent. The most important part that needs to be noted about this data is that it was collected by the local government and not an outside, unbiased third party. Therefore, like with anything, should it be taken with a grain of salt? As with any situation where data is being observed, the first question that should always be asked is who is collecting the data and why? Could it be serving any private interests and contain bias? With any data, there is always even the slightest inherent bias in data collection, so no dataset, including this one, should be taken without dispute as purely factual.

To look at divestment and evictions, let's first discuss those words and how we are defining them. Divestment in terms of municipal or city development is when one area of a city, in this case we are looking at neighborhoods, is abandoned or neglected. An example of this is the [South Bronx in the 1970s](https://www.versobooks.com/blogs/3145-benign-neglect-and-planned-shrinkage). Eviction is defined as the expulsion of a tenant from a property. Another interesting point to how much SF grew shown in Fig. 1 below graph that shows how much money through new developments measured by the money in building permits poured into SF in the neigh of the tech boom. 


![Fig 1](/images/SanFranciscoHeatMap.png)
**Fig 1 Growth as measured by cost of new developments over the last two decades**


It should also be noted that this graph only goes up to 500 million to keep it easily interpretable, but that anything over 500 million is just capped at that number and grouped into that category. As this figure shows, there has been a large amount of growth. However, it can be noticed that there are some more concentrated areas, notably it appears to be “centered” around the downtown area of SF. This makes sense as many businesses came in, and then with an influx of people, people would want to live close to their work. But this just shows big concentrations of wealth. So another way to look at the money being poured into SF is in Fig. 2 below. 


![Fig 2](/images/Average_Cost_per_UnitSanFrancisco.png)
**Fig 2 Average cost of new unit by neighborhood over last two decades**


Fig. 2 depicts the average cost of a new unit per neighborhood in the past two decades. There are some neighborhoods that are more expensive than others, Chinatown being much less expensive compared to other neighborhoods, but besides this point, there is a smooth curve in the increasing prices over the past two decades for the neighborhoods of SF. For one part of the explanation on why Chinatown has such a difference in living expenses, [check out this article](https://www.sfchronicle.com/bayarea/article/Families-live-jammed-into-Chinatown-rooms-with-6663902.php).

But the point is that things seem pretty “normal”, nothing sticks out. If you think about this, you may first think, “Okay, everything developed and got more expensive as the city had a tech boom and grew in size and developments to make room for more people coming in”. If you start to talk with locals, however, there are some neighborhoods where people who have historically lived there and have roots established in certains neighborhoods are being priced out like crazy, and these graphs don’t show it. Remember when we talked about what bias may be hidden in data and data collection? 

Historically, as with any city, San Francisco has priced out low income people who are disproportionately people of color. One of the most known examples of this is [The Filmore](https://sfpublicpress.org/news/2019-09/fillmore-revisited-how-redevelopment-tore-through-the-western-addition) which used to be the historic black neighborhood in SF that was heavily gentrified and led to massive amounts of displacement of SF residents, many into what is now known as the neighborhood of The Western Addition. It should also be noted The Fillmore used to have a very heavy Japanese population, many of whom were removed due to Japanese internment. While [Japanese internment](https://theculturetrip.com/north-america/usa/california/articles/japantowns-hidden-history-how-internment-camps-shaped-san-francisco/) was occurring, there was also a massive influx of Arican-Americans into SF for jobs and to escape openly enforced Jim Crow laws in the South. This timing led to The Filmore then becoming one of SF’s historically black neighborhoods. 

Another example of a neighborhood where this has occurred is The Mission. The Mission is, historically, one of the heavily [LatinX neighborhoods](https://www.sfgate.com/neighborhoods/sf/mission/) in SF. Like many neighborhoods in SF unfortunately, though, any SF native or person who has been in the city long enough can tell you its residents have been facing massive levels of displacement for years. So much so that some of its circumstances were compared to those of the [South Bronx](https://sf.curbed.com/2016/8/10/12407266/mission-district-san-francisco-fires-arson) when there was a string of fires that then led to new “four dollar sign” restaurants being put in their place. Fires to displace individuals is one of the “telltale” signs of gentrification and divestment. SO, does our data exploration confirm this?



![Fig 3](/images/unnamed.png)

**Fig 3 Evictions by neighborhood over last two decades**

![Fig 4.](/images/unnamed-2.png)

**Fig 4 City average with cost per development of four lowest eviction neighborhoods with mission and citywide average**


So, from these graphs, it does! Fig. 3 shows that The Mission’s eviction rate compared to that of other neighborhoods is significantly higher. We do want to mention that we did not calculate this as an average of the number of people in each neighborhood, so it is not completely accurate because there was no easy dataset that had the population per neighborhood. However, that being said, this is still shocking! That is a major difference. Fig. 4 how many evictions per year for The Mission compared to some of the neighborhoods with the lowest eviction rates. This shows a few things. First, it shows the disparity of evictions between those neighborhoods with high vs low evictions rates, i.e. showing these rates are nowhere near close. This then poses the question of could this be proportionate? Especially when you look at how for the other four neighborhoods that are not The Mission on Fig. 4, there is not much fluctuation in their numbers of evictions while the trend line of The Mission does not seem to level out until much closer to 2020. That's strange, why is it so different? The lack of “up and down” in the other four neighborhoods also brings us to the next point of why did The Mission’s trend line fluctuate so much? Why did it get normal? This is also strange because as you can see with other trend lines, it's not normal to move up and down that much. 

So looking at Fig. 4 again, one thing that is also immediately noticeable is how high the number of evictions The Mission starts at in 2000. It is massive compared to other neighborhoods. Even considering those other neighborhoods are all some of the lowest in terms of overall eviction, notice how they are clustered? Then think back to Fig. 3, The Mission is not a part of any cluster, it is completely by itself? But this is strange because The Mission has a normal amount of cost per unit and new development going into it compared to other neighborhoods? If you go back up to Fig. 2, The Mission does not stand out at all. So, what does this mean, especially in terms of our underlying question of if there is a correlation of high eviction rates and divestment?

What we see as data scientists is that then there is no correlation between high eviction rates and divestment then. As Fig. 5 below shows, The Mission is able to charge a decent amount of money on average. Fig. 5 shows The Mission as well as the city average and a few other randomly chosen neighborhoods. 



![Fig 5.](/images/unnamed-3.png)

**Fig 5 Average cost of New Development in Mission, city average, and few other neighborhoods**


In fact, from Fig. 5, one would argue that there must not be any divestment occuring in the city as it is able to charge more than the average cost per unit, so this could mean there is a lot of “money flowing” in The Mission? Fig. 5 shows us that there are new developments going in, so it would appear that The Mission is not being abandoned, i.e. there is no disinvestment. Along with that, Fig. 1 shows us that the cost per unit of new development in The Mission is not necessarily noteworthy. So this would mean that we could come to the conclusion that in the case study example of The Mission we have been exploring, while there are high eviction rates, there is also a high cost per unit in new developments. But something still seems to be off, how can a neighborhood be charging so much for cost per unit, which did increase for a while even before decreasing again, while still having disproportionately high eviction rates compared to other neighborhoods? Why does it feel like we are missing something?

Remember how it was mentioned that all data needs to be taken with a grain of salt? Any SF native or individual who has lived in San Francisco for a while would tell you that there’s something else going on in The Mission that our data is not capturing. Think back to the fact of how there were fires in The Mission that were displacing people. It seems important, but how would you capture that in this data? This is one of the most important parts of relying on data without working to understand a situation- is that data can be biased and miss part of the story. Anyone’s gut could tell you something is off here. What is happening, as our data has shown, is that The Mission is an “up and coming” or “hot” neighborhood as we have seen pretty much overall an increase in the cost per unit since the tech boom. Along with that, we saw a drastic decrease in the number of evictions in the 20 years since the tech boom was really big in SF, although the eviction rates are still high. So, the proving of the increase in the average cost per unit is historically one of the tell tale signs of gentrification. It should also be noted there was a massive number of eviction rates which eventually decreased then flattened out around 2010 as seen in Fig. 6, compare this to Fig. 7 which has a decently level, even decreasing average cost per unit in new development. However, around 2010, that average cost per unit of new development started seriously increasing. 

![Fig 6.](/images/unnamed-4.png)

**Fig 6**

![Fig 7.](/images/pasted image 0.png)

**Fig 7 **

We did not check to see if there is a mathematical correlation between the two to prove that the number of evictions is related to the cost per unit in new developments in a neighborhood though there may look to be one, but that is okay. That is not the point. What we found in our analysis is how careful you truly have to be around where you get your data from and how the inherent bias all data comes with. We could have stopped and said there is no correlation, but that would have only been telling half of the story with the data.




