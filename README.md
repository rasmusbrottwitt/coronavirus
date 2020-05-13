# Covid 19 and the world 

2020 has been a year that will go down in history, remembered for the COVID-19 pandemic. It is not the first or worst pandemic in world history to say the least, but it is the first time it has happened to our modern society. We have the opportunity to track the spread to a very hight level of detail, and at the same time see and uncover it's impact on all aspects of society in real time. 

In that way, the Corona Virus is more than just a disease - it is a shift in how our world works, and has the potential to  hit the economy really hard. The reasoning for this is more complex - we have to understand how the virus' effects spread physically and psyhologically, and then look at how it has impacted the economy. 

This article will look at the spread of the virus itself and the fear and awareness following, to see how and why the countries have had to lock down. Following this, the article will look into the American Economy and see how it has been hit by the virus on different levels - and why it might be a lot different than you expect. 

## The spread of Corona Virus
The Corona Virus started as a new disease in China, and became more and more reknown to the world as stories and images from Wuhan leaked. After reaching Italy in February, it stared spreading to the rest of the world and was declared a pandemic in mid March.

<iframe 
        src="Charts/webpage006.gif"
        width="900" height="500"
        frameBorder="0"
></iframe>

It's growth has been rapid ever since then and the outbreak in China now looks like almost nothing.

<iframe 
        src="Charts/webpage001.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

The reason for the massive impact and actions from the governments are very clear when plotting out deaths world wide - the spread went from one country to globally, with the deathrates following. Hover over the interactive map to get countrywise details or zoom in to specific places to obtain increased local overview. 

<iframe 
        src="Charts/webpage004.html"
        width="900" height="450"
        frameBorder="0"
></iframe>

As shown earlier, the growth is near exponential - so to gain a better picture of the spread, a logarithmic transformation has been applied to the numbers. Here, the relationship between confirmed cases and deaths, also known as the mortality rate, looks constant. 

<iframe 
        src="Charts/webpage002.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

However by diving deeper into the numbers we see another picture. Since the outbreak of the virus as a Pandemic, the mortality rate has actually doubled, from 3% to around 7%. 

<iframe 
        src="Charts/webpage003.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

And looking at the mortality rate on a global view, it is clear that it varies from country to country. Hover over map to get detailed information.  

<iframe 
        src="Charts/webpage005.html"
        width="900" height="460"
        frameBorder="0"
></iframe>

There are many possible factors of the change in mortality rate. An unknown variable is testing strategy and number of tests, as well as the possibile effect of the tuberculosis vaccine which still is a mandatory vaccine in many development countries. The following article investigates this much futher. (https://www.clinicaltrialsarena.com/news/australia-bcg-vaccine-trial-covid-19/). 

The largest factor in the combat of the disease for now has been the massive lockdowns almost every country has done. However, some countries have deffinetly hesitated, most likely because of the consequences on the economy. So, what effect did these lockdowns have - and did the timing matter? 

### Spread and lockdown in different countries
Many countries started considering lockdowns early on based on recommendations from WHO. By locking the country down and distancing physically from each other, the virus would not spread as rapdily and the health care systems would be able to maintain normal function as well as having capacity for infected COVID19 patients. On the other hand, if everybody continued to live as normal, the system would be overflown by patients and not be able to treat regular diseases as well as everybody infected with COVID19. 

These two scenarioes have been showcased many times in different formats, here as seen in The New York Times (https://www.nytimes.com/article/flatten-curve-coronavirus.html). The scenarios are the green and red cruve respectively.

<iframe 
        src="Charts/curve.png"
        width="900" height="400"
        frameBorder="0"
></iframe>


The spread in different countries, and especially also the number of deaths, appear to be very different. To gain an understanding of why this is the case, let's look into the rate that each country locked down compared to the casualties. 

In the following maps, the dahsed line indicates lockdown dates, and its color matches the countrystats. 

<iframe 
        src="Charts/webpage006.html"
        width="900" height="450"
        frameBorder="0"
></iframe>


It is seen that the casualties caused by the virus exploded suddenly in the US, and that the US clearly is on the red curve from the before mentioned New York Times visual. In comparison, countries as Canada and Denmark currently stay close to the blue curve. The dashed vertical lines indicate the lockdown date for each country. 

A quick glanse at the visual shows a trend in timing of lockdowns and the consequences here off: if lockdown happens early, fewer casuslaties occur. This matches well with the recommendations from WHO and epidemology experts. 

By comparing time from first death in a country to time of lockdown, this picture is even clearer. Denmark and Canada, who both made national lockdown before first death, has a much flatter curve than those who waited. Below is a logarithmic weighted plot comparing casualty numbers of different countries.  

<iframe 
        src="Charts/webpage007.html"
        width="900" height="450"
        frameBorder="0"
></iframe>


Lockdowns seem to work. The countries that locked down the fastest had the greatest reduction and stabilization in number of cases. Furthermore, it is clear that growth rate has declined following a lockdown regardless of timing and strategy. By looking a bit deeper into timing and effect of lockdowns, it also becomes clear that the United States' rate was by far the highest - until the lockdown 24 days after first death. 

<iframe 
        src="Charts/webpage008.html"
        width="900" height="450"
        frameBorder="0"
></iframe>

This shows that if or when a new pandemic hits, quick actions from governments and responsible actions of individuals definetly seem to add up. 

### Predicting the (near) future
It is now obvious that lockdowns seem like a good idea - but is it possible to predict how big the impact is going to be? 

In general, predicting the future is hard - and in this case even more so. The society is in an unpresedented situation, and all goverments are constantly shifting directions to limit the spread and effects. However, given the status as it is, is it possible to get an idea of the direction the different countries are headed in by applying math to historic and demographic data.

<iframe 
        src="Charts/webpage009.html"
        width="900" height="450"
        frameBorder="0"
></iframe>

As it can be seen, some countries are still on the rise, and some have definetly flattened the curve. The predictions of the near future of casualties can be seen after the grey line indicating today. China and Italy seem to have had their hit, and the curves are starting to flatten. The same can be said for Denmark, while UK, US and Canade are sill on a rise. 

### Potential reopening
Following the lockdown and the flattening of the curves, the natural next step would be to look at when to open up again. For every day the country is closed, money is slipping out of the economies, and governments have to write big checks to keep the wheels going for companies and individuals. 

To do this is it necessary to look at the true number of infected. The average time from infection to death is 17 days. This means that if the true mortality rate is 1% then if 1 person dies today there was 100 infected 17 days ago. This information can together with the average growth rate for the virus be used to give an estimate of the true number of infected in each country.
<iframe 
        src="Charts/webpage010.png"
        width="900" height="350"
        frameBorder="0"
></iframe>

This clearly shows why it would be very interesting to know the actual mortality rate. A relatively small change in the mortality rate assumption from 3% to 1% makes a huge difference in the actual number of infected. This is very important information to know when planning a reopening of a country like the US. 

However, one thing is for sure - the number of confirmed cases are in all scenarios way lower than the actual amount of cases and should not be trusted blindly. 


All the information adds up to a clear story. The disease spread rapidly from Wuhan to the rest of the world, and as the epidemic became a pandemic the mortality rate did not slow down despite our great efforts. However, lock downs are a great idea to halt the spread, and fast actions have produced great results. 

It is clear that the disease should be taken seriously, both because of the death rate and the lockdowns necessary to stop the spread. And by looking at the social media awareness, it is clear that people are very aware - and have started growing as concerned of the concequences to the economy as to the virus itself. 

## Social Media Data from Twitter
1.308.276 tweets made between March 12th and April 30th containing country codes has been gathered. It can be seen that the awareness in europe is very high - also compared to US. By zooming into US on the interactive map is it clear that the main social media attention concerning the virus in US is along the coastlines, while central US has show little to minor awareness online. 

<iframe 
        src="Charts/webpage013.html"
        width="900" height="550"
        frameBorder="0"
></iframe>

By looking at a couple of potential buzz words for the awareness - "Just a flu", "Apocalypse", "Stayhome", "Economics" and "Reopen" can an idea of how the awareness has intensified and behaved be formed. 

The included bars shows the key events that took place in the Unites States. 

<iframe 
        src="Charts/webpage011.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

Many interesting trends can be seen in the above chart. First of all does it seem like the closing of schools and sport leagues kick starts the american puplic COVID19 attention on twitter. 

It can be seen that both the "just a flu"-tweets and the "Apocalypse"-tweets is peaking around this date. However since the peak has both the amount of "just a flu"-tweets and the "Apocalypse"-tweets been steadly decreasing. It certainly looks like people found out that this not is our doom as humans but neither just a basic flu. 

In general is the amount of tweets concerned about economics and preventing spread almost the same. In other words does the economics consequense of the virus get just as much attention as how to avoid the virus spread. When looking only at the "Economics"-tweets trend can it be seen that a big increase in social media attention happened the same day as US had been in lockdown for almost a month and the gonvernment made a statement with no reopening insight. This is also the date where the 'Reopen!'-tweets starts to increase. ¨

However, to focus the attention on the reactions to the economy has some extra buzzwords regaring the publics perception of the economy been added - "Unemployment", "Economy" and "Financial Crisis". 

<iframe 
        src="Charts/webpage012.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The analysis how a weekly trend in the 'Unemployed'-tweets. Futher investigation showed that these tweets peak the same day as the weekly official unemployment number report surfaces. This trend has been happening since few days after the lockdown officially started. Futhermore is a huge jump in tweets about economy happening the day where the government states that no reopening is insight. This clearly shows the people's high concerns with the economic situation that the lockdown causes which also often has been compared to the financial crisis in 2008. 

So - let investigate how the American Economy is behaving - for the individual, state and companies. 

## US ECONOMY
The US economy is a weird size, containing many variables. The investigation will look into the general movements the last 40 years, especially from the largest companies, how the banks are behaving, and lastly the unemployment rate to see how the individual is affected. 

The Dow Jones index contains the 30 largest companies - and looking at the companies isolated gives us an idea of how the crisis rattles the market heavily. 

<iframe 
        src="Charts/webpage014.html"
        width="900" height="550"
        frameBorder="0"
></iframe>

But aggregating them is a good relfection of how the economy has behaved over time. 

<iframe 
        src="Charts/webpage015.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

Some historic moments, especially seen from a financial perspective, are remarkably clear

- The rise and burst of the IT bubble
- The Financial Crisis 
- Covid 19

For reference, Sars has also been annotatated to show its lesser significance on the market. 

As it can be seen, the Dow Jones has grown since it was introduced in 1986, with some smaller and larger bumps on the way. 

A zoom in to the recent years after the financial crisis, show that the Dow Jones has dropped rapidly during the corona pandemic after several years of growth - but now has seen a rise again. 

<iframe 
        src="Charts/webpage016.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

Compared to the last recent large drop in value, the Financial Crisis, some major differences is seen
<iframe 
        src="Charts/webpage017.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The changes in movements here are obvious: 

- In the financial crisis, concerns grew over time leading to a long decline followed by a sharp drop
- With the Corona Virus, the shock was abrupt - but somehow the shock seemed to have had a lesser imidate impact. 

The pattern is clear to narrow down to a single line: 

**The financial crisis was caused by a rotten economy, with fragile and fraud loan structures. The Corona Virus was a result of a shock. Therefore, the value of the market reflected this.**

But still - The world frequently hear about massive issues in the American Economy, so why are the stocks not lower? 

A main reason is the Federal Reserve who printed a lot of money in late March to combate the drop in stocks - which resulted in the best day in Dow Jones ever value-wise, and one of the four largest relative speaking! https://www.theguardian.com/world/2020/mar/24/coronavirus-data-shows-biggest-hit-to-business-activity-since-records-began

<iframe 
        src="Charts/webpage018.png"
        width="900" height="800"
        frameBorder="0"
></iframe>

So - for now the largest companies in America are doing relatively well, because of aid from the government. 

The next part will keep the focus on the Corona Crisis compared to the Financial Crisis of 2008, but shift over to the banks. 

### Banks
It has now been investigated briefly how the stock market in general was affected. Now lets look at the big six banks in America - namely the banks noted too big to fail! 

"Too big to fail" describes a financial institution whose collapse would cause unsavable damage to the American economy.
The government will try to  intervene in situations where failure poses a grave risk, and save the economy from total collapse. 

Banks that the U.S. Federal Reserve has said could threaten the stability of the U.S. financial system are long - but this analysis has focused on the largest players. 

Plotting them out shows how big they were during the mid 2000's, and how hard the financial crisis hit them. 

<iframe 
        src="Charts/webpage019.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

And by zooming in on 2019-now, we see that the hit was not as bad as feared by some for the Corona Virus. 

<iframe 
        src="Charts/webpage020.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

The reason why is a mix of a slight change in structure for these too big to fail companies, the federal reserve printing extra money and that the banks are simply not as overvalues now as they were back in 2008. 

## Unemployment
A major reason of concern for both the banks and government, but especially the individual is the unemployment rate. Part of the initial reason for the collapse in 2008 was that people were not able to pay their mortgages - and the largest reason for people not being able to pay their rent is being unemployed.  

An obvious question is why would people become unemployed now, when the companies are not suffering too hard during lock down? Part of the answer is simple: many of these companies are not suffering because they lay off their employees while they are closed during the lock down. 

<iframe 
        src="Charts/webpage021.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

Looking at the unemployment rate, it seems like the highest spikes are around the financial crisis and back in the 1980's. 

But zooming in on 2019-2020 shows that the most recent datapoint is just too close to the border to see

<iframe 
        src="Charts/webpage022.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The unemployment has more than trippled from March to April, going from 4.4 to 14.2 percent of the American population. The unemployment rate has simply never been higher. 

This is a major concern for the American economy. 

# Conclusion
By diving into the numbers and articles presented, there are some conclusions that can already be made: 

- The virus has spread quickly and is still going on. The mortality rate is high - but maybe there are some dark numbers and unknown variables. 
- Earlier lockdown correlates with less casualties. 
- The attention of the disease escelated fast, and especially concerns about the economy as soon as the American government started taking action
- The American economy is at a glance doing well, and has even had it's best day ever, but this is mainly because of some of the tools the government are leveraging at the moment. 
- Underneath the wellbeing of companies, a huge unknown is bubbling: unemployment. History shows us this could result in catastrophic impacts on the nation. 

However, the numbers and our first conclusion also shows that this is an ongoing pandemic and far from over. We have to learn from what we have done so far, what has happened in the past and adjust accordingly to prevent large consequences on our health, economy and wellbeing. 

## References and datasets
