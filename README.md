# Covid 19 and the world 
*Analysis and data last updated May 13th 2020*

*By Kasper Emil Nielsen (s153845) and Rasmus Boldvig Rottwitt (s200348)*

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

This is howeber most likely not the actual case. Countries are not testing all individuals, and testing strategies change all the time. The most likely explanation for the large fluctuation in mortality rate is simply a change in testing strategy - for instance,  Denmark went from testing only severely ill, to more and now to random tests (https://www.yourdanishlife.dk/coronavirus-update-change-in-testing-strategy/). Denmark's curve is propably opposite of the global curve, since in a global perspective the rate between tested and deaths is propably decreasing due to the rapid growth in cases. 

Looking at a world map showing the mortality rate, it is clear that it varies from country to country. Hover over map to get detailed information.  

<iframe 
        src="Charts/webpage005.html"
        width="900" height="460"
        frameBorder="0"
></iframe>

There are many possible factors of the change in mortality rate, and another large unknown variable is the possibile effect of the tuberculosis vaccine which still is a mandatory vaccine in many development countries. The following article investigates this much futher. (https://www.clinicaltrialsarena.com/news/australia-bcg-vaccine-trial-covid-19/). 

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


Lockdowns seem to work. The countries that locked down the fastest had the greatest reduction and stabilization in number of cases. Furthermore, it is clear that growth rate has declined following a lockdown regardless of timing and strategy. By looking a bit deeper into timing and effect of lockdowns, it also becomes clear that the United States' rate was by far the highest - until the lockdown 24 days after first death. That is about a week more of uncontroled spread than UK and Italy who had lockdown at the aproximately same time since first death.

<iframe 
        src="Charts/webpage008.html"
        width="900" height="450"
        frameBorder="0"
></iframe>

This shows that if or when a new pandemic hits, quick actions from governments and responsible actions of individuals definetly seem to add up. 

### Predicting the (near) future
It is now obvious that lockdowns seem like a good idea - but is it possible to predict how big the impact is going to be? 

In general, predicting the future is hard - and in this case even more so. The society is in an unpresedented situation, and all goverments are constantly shifting directions to limit the spread and effects. However, given the status as it is, is it possible to get an idea of the direction the different countries are headed in by applying math to historic and demographic data.

Hover over the chart to see the forecasted values. 

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
As with every other global event, people started discussing everything around it as soon as it hit the news. 1.308.276 tweets made between March 12th and April 30th containing country codes have been gathered. It can be seen that the awareness in europe is very high - also compared to US. By zooming into the US on the interactive map is it clear that the main social media attention concerning the virus is along the coastlines, while central states has show little to minor awareness online. 

<iframe 
        src="Charts/webpage013.html"
        width="900" height="450"
        frameBorder="0"
></iframe>

By looking at a couple of potential buzz-words for the awareness - "Just a flu", "Apocalypse", "Stayhome", "Economics" and "Reopen"  an idea of how the awareness has intensified and behaved becomes clear. 

The included bars shows the key events that took place in the Unites States (https://en.wikipedia.org/wiki/Timeline_of_the_COVID-19_pandemic_in_the_United_States).  

<iframe 
        src="Charts/webpage011.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

Many interesting trends can be seen in the above chart. First of all it seems like closing of schools and national sporting leagues kickstarts the american puplic COVID19 attention on twitter. 

It can also be seen that the tweets containing "just a flu" and  "Apocalypse" peak around this date. However since then  the amount of "just a flu" and "Apocalypse"-tweets have been steadily decreasing. It certainly looks like people found out that this not the end of human kind as we know it, neither simple a simple seasonal flu. 

In general the amount of tweets concerned about economics and preventing spread are almost the same. In other words the economics consequenses of lockdown gets just as much attention as how to avoid spreading the virus. 

When looking only at the "Economics"-tweets it can be seen that a big increase in social media attention happened the same day as the US had been in lockdown for almost a month and the gonvernment made a statement claiming no intent to start reopening. This is also the date where the 'Reopen!'-tweets started to increase. 

However, to get a more broad view of the shifting attention from fear of disease to fear of collaps of the american economy, another set of buzzwords are interesting to look at - specifically "Unemployment", "Economy" and "Financial Crisis". 

<iframe 
        src="Charts/webpage012.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The analysis shows a weekly spike in the 'Unemployed'-tweets. Futher investigation showed that these tweets peak the same day as the weekly official unemployment number report surfaces. 

This trend has been happening since few days after the lockdown officially started. Futhermore a huge jump in tweets about economy started the day the government announced that the lockdown would continue indefinetly. This clearly shows the people's high concerns with the economic situation caused by the lockdown, and comparisons to the financial crisis in 2008 started appearing online. 

But how many of these concerns are grounded in the actual state of the American economy? Have we not learned anything from the collapse in 2008 - and is the situation even comparable? An analysis of the history and structure of the different elements in the American economy and their influence on each other might give us an answer. 

## US ECONOMY
The US economy is a complex matter, containing many intertwined variables. The investigation will look into the general movements the last 40 years, especially from the largest companies, how the banks are behaving, how money is structured and lastly how the individual is affected and vice versa. It might get a bit complex - but hang tight, the conclusion is as dramatic as it is unambiguous. 

The Dow Jones index contains the 30 largest companies (https://en.wikipedia.org/wiki/Dow_Jones_Industrial_Average) - and looking at these individually gives us an idea of how the lockdown rattled a steadily moving market suverely. 

Hover over the stocks to see individual stock values.

<iframe 
        src="Charts/webpage014.html"
        width="900" height="550"
        frameBorder="0"
></iframe>

This shows how the virus - and especially the lockdown and the consequences - came as a shock to the largest private economies in America, ratteling their foundation and idea of the near future. However, this is only a snapshot of the market, showing that we went from a generally steady period in time into something crazy. Aggregating them and looking at them over the last decades shows how the economy has behaved over time, and might uncover if this is totally new territory or just a new factor. 

<iframe 
        src="Charts/webpage015.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

As it can be seen, the Dow Jones has grown since it was introduced in 1986. Clearly, the market has it's ups and downs, some more drastic than others. Some historic moments with great impacts on the economy are remarkably clear

- The rise and burst of the IT bubble (mid 2002)
- The Financial Crisis (mid 2008)
- Covid 19 (present)

For reference, Sars has also been annotatated to show its lesser significance on the market. Many feared Sars would turn into a pandemic - but since it didn't, it is clear from the movements in the economy that the fear did not have an effect compared to the lockdown to stall the coronavirus. 

A focus on the recent years after the financial crisis, show that the Dow Jones has dropped rapidly during the corona pandemic after several years of growth - but the last weeks it has seen a rise again. 

<iframe 
        src="Charts/webpage016.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

Compared to the previous large drop in value, the Financial Crisis, some major differences are clear

<iframe 
        src="Charts/webpage017.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The financial crisis was a long period of build up, followed by months of steady decline to almost half of the peak value, and culminating with a huge drop following the collapse of the Lehman Brothers (https://en.wikipedia.org/wiki/Bankruptcy_of_Lehman_Brothers). Then, years of stabilisation and steady growth followed. 

On the other hand with the Corona Virus pandemic, the shock was abrupt and the market declined rapidly over a few days or weeks from 30000 billion USD to 18000 billion USD - almost a 40% drop in no time. But following this massive drop, the shock seemed to have had a lesser imidate impact - and even a massive bump up. 

Basically, the situations are completely different, but both have had huge effects on the future of companies. The financial crisis was caused by a rotten economy, with fragile and fraud loan structures. Essentially, the banks had way less money than they thought, and a lot of people had mortgages they could never pay - meaning the banks had value (houses) they could not turn into money. Lots of unemployed people with no money or places to live meant troubled times ahead for companies selling - and combined with the market not having as much money as expected, the value dropped. 

The drop folowing the Corona Virus was a result of a shock of the incoming global lockdown and the news that people would not be buying on the market in the near future. Therefore, the value of companies fell drastically - no buying means no selling, and no selling means no money in the bank. Therefore, lots of companies have had to lay off employees and find ways to stay a float. However, as it can be seen, the value quickly went back to normal and the Dow Jones even had it's best day ever in absolute change, and top 5 relatively speaking.  

<iframe 
        src="Charts/webpage018.png"
        width="900" height="750"
        frameBorder="0"
></iframe>

The main reason is not more faith in the market or current handling of the virus - but the news that the Federal Reserve would start printing more money in late March to compensate the drop in stocks and market. (https://www.theguardian.com/world/2020/mar/24/coronavirus-data-shows-biggest-hit-to-business-activity-since-records-began)

So - for now the largest companies in America are doing relatively well, because of aid from the government. 

### Banks
It has now been investigated briefly how the stock market in general was affected. However, the American Economy not only roots on private companies selling and buying, but also on banks investing, saving money and helping individuals and companies borrow money to keep the economy moving. 

A bank is therefore responsible for much of the structure of movement of money in modern society, and if a bank is simply too intertwined with the state of the nation they are labeled too big to fail. "Too big to fail" describes a financial institution whose collapse would cause unsavable damage to the American economy, simply because so much money on different levels of society and scale are tied up by their structure (https://en.wikipedia.org/wiki/Too_big_to_fail).
The government will try to intervene in situations where bankrupcy lures, and save the economy from total collapse. 

The list of banks that the U.S. Federal Reserve has said could threaten the stability of the U.S. financial system are long - but this analysis has focused on some of the largest players. 

Plotting them out shows how big they were during the mid 2000's, and how hard the financial crisis hit them. 

<iframe 
        src="Charts/webpage019.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

Essentially, without aid from the government they would have gone bankrupt - and the United States would most likely have followed. 

And by zooming in on 2019-now, we see that the hit following the devaluation of the economy caused by the lockdown was not nearly as bad as feared. 

<iframe 
        src="Charts/webpage020.png"
        width="900" height="500"
        frameBorder="0"
></iframe>

The reason why is a mix of factors: a slight change in structure for these too big to fail institutions, the federal reserve printing extra money and that the banks are simply not as overvalued now as they were back in 2008. 

However - they still heavily rely on people paying their mortgages. And as mentioned, many companies have had to lay off large quantities of employees to stay afloat. As mentioned, the American economy printed extra money and have written checks to comapanies to help them stay alive - but compared to the danish model where a lot of money is direcly allocated to the individual worker throught the company (for instance, paying 30% of the sallary to workforce that were sent home instead of firing them(https://www.copcap.com/covid19-wage-compensation)) financial help in the US is simply just written out to the company to survive how they can. Also, help packages to individuals come directly from the state, in form of food or blank checks (https://www.bbc.com/news/world-us-canada-52405275).

This means people are still loosing their jobs, even though the companies are getting aid to stay alive. 

## Unemployment
A major reason of concern for both the banks and government, but especially the individual is the unemployment rate. Part of the initial reason for the collapse in 2008 was that people were not able to pay their mortgages - and the largest reason for people not being able to pay their rent is being unemployed.  

A look at the unemployment rate shows spikes have happened over time. Especially in the mid 80s and the aforementioned Financial Crisis.

<iframe 
        src="Charts/webpage021.png"
        width="900" height="550"
        frameBorder="0"
></iframe> 

But zooming in on 2019-2020 shows that the most recent datapoint is almost too close to the border to see - and higher than ever.

<iframe 
        src="Charts/webpage022.png"
        width="900" height="550"
        frameBorder="0"
></iframe>

The unemployment has more than trippled from March to April, going from 4.4 to 14.2 percent of the American population. The unemployment rate has simply never been higher. And as mentioned, unemployed people means trouble. No payments for banks, if the banks don't have money the companies won't have money, and if the companies don't have money they go bankrupt - and the circle continues. 

This is a major concern for the American economy, and probably soon more so than the virus itself. 

# Conclusion
By diving into the numbers and articles presented, there are some conclusions that can already be made: 

- The virus has spread quickly and is still going on. The mortality rate is high - but there are some dark numbers and unknown variables that are essential to take care of.  
- Earlier lockdown correlates with less casualties. 
- The attention of the disease escelated quickly, and especially concerns about the economy as soon as the American government started taking action
- The American economy is at a glance doing well, and has even had it's best day ever, but this is mainly because money is going straight to the companies instead of the individuals. 
- Underneath the wellbeing of companies, a huge unknown is bubbling: unemployment. History shows us this could result in catastrophic impacts on the nation. 

However, the numbers and our first conclusion also shows that this is an ongoing pandemic and far from over. We have to learn from what we have done so far, what has happened in the past and adjust accordingly to prevent large consequences on our health, economy and wellbeing. 

*For further analysis, comments and calculations visit or download our GitHub repo at the top of the page*

[Explainer Notebook](https://mybinder.org/v2/gh/rasmusbrottwitt/coronavirus/master?filepath=ExplainerNotebook.ipynb "Explainer Notebook")
