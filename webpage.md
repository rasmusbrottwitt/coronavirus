# Covid 19 and the world 

2020 has been a year that will forever be remembered for the COVID-19 pandemic. It is not the first pandemic in world histori to say the least, but it is the first time it has happened to our modern society. We have the opportunity to track the spread to a very low detail, and at the same time see and uncover it's impact on all aspects of society. 

In that way, the Corona Virus is more than just a disease - it is a shift in how our world works. We will start out by looking at how the virus has spread and what is in store in the near future, regarding casualties and contamination. Then, we will try to uncover it's impact on some of the ground pillars of society, being social media and the economy - and in this instance specifically Twitter and the American Economy. 

### The spread of Corona Virus
The Corona Virus started as a new disease in China, and became more and more reknown to the world as stories and images spread. After reaching Italy in February, it stared spreading to the rest of the world and was declared a pandemic in mid March. It's growth has been rapid ever since then. 

FIG 1 - COVID 10 WORLD WIDE DEVELOPMENT

The reason for the massive growth is very clear when plotting out deaths world wide - the spread went from one country to globally, with the deathrates following. 

FIG 5 - World Map gif

The mortality rate appears to have been close to contant since the spread, which is clear in a logarithmic view of the relationship between confirmed cases and deaths. 

FIG 2: LOGARITHMIC COVID19 WORLD WIDE DEVELOPMENT

However, since the outbreak as a Pandemic, the mortality rate has actually increased from 2-3% to around 6%

FIG 3: COVID 19 MORTALITY RATE

Given the massive increase in cases and mortality rate, it makes sense to lock down the world in some degree. 

### Spread and lockdown in different countries
The spread in different countries, and especially also the number of deaths, appear to be very different. To gain an understanding of why this is the case, let's look into the rate that each country locked down in compared to the spread. 

BOKEH 1 

We see how the virus deaths exploded suddenly in US and that US clearly is on the red curve. In comparison is countries as canada currently staying at the green curve. The dashed vertical lines indicates the lockdown date for each country. We see a huge different between Denmark and Canada that makes national lockdown before any deaths has arise, and clearly are on the green curve, compared to US, UK, and Italy which all made national lochdown pretty late when above 300 deaths had happened and clearly are on the red curve. Especially the United States seem to have exploded in number of casualties. 

By comparing time from first outbreak to time of lock down, we see a clear picture

BOKEH 2

Lockdowns seem to work. The countries that locked down the fastest had the greatest reduction and stabilization in cases. By looking a bit deeper into timing and effect of lockdown, it also becomes clear that the United States rate was by far the highest - until the lockdown. 

BOKEH 3

This shows that if or when a new pandemic hits, quick actions from governments and responsible actions of individuals definetly seem to add up. 

### Predicting the (near) future
Now we see that lockdowns seem like a good idea - but can we possibly predict how big the impact is going to be? 

In general, predicting the future is hard - and in this case even more so. We are in an unpresedented situation, and all goverments are constantly shifting directions to limit the spread and effects. However, given the status as it is, we can get an idea of the direction we are heading in.

PLOT of predicted vs actual values for country.

As it can be seen, some countries are still on the rise, and some have definetlu flattened the curve. China and Italy seem to have had their hit, and the curves are starting to flatten. The same can be said for Denmark, while UK, US and Canade are sill on a rise. 

BOKEH 4

To understand how the pandemic will continue to spread, we have applied prediction models to the data gathered, and predicting how the spread looks the next couple of days. 

### Potential reopening
Following the lockdown and the flattening of the curves, the natural next step would be to look at when to open up again - and to do this we can look at the true number of infected. The average time from infection to death is 17 days. This means that if the true mortality rate is 1% then if 1 person dies today was there 100 infected 17 days ago. This information can together with the avg. growth rate for COVID19 be used to give an estimate of the true number of infected in each country.

