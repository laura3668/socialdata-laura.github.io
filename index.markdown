---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Home
---
# Global Life Expectancy: What Social Factors Reveal About Our Lifespan
_By Cecilie Mai Do & Laura Pascual Hebrero_  

![image](/images/front-picture.jpg)

When we think about life expectancy, we often focus on factors like healthcare access, diet, and genetics. But what if the secret to a longer life lies not in our physical bodies, but in the social forces around us? Recent studies suggest that the quality of our relationships, our mental health, and the social structures we navigate also play an important role in determining how long we live. Research from the [World Health Organization](https://www.who.int/health-topics/social-determinants-of-health) highlights how social determinants of health, such as community support and socioeconomic conditions, significantly influence lifespan outcomes. The connections we maintain with family and friends, the support systems we have in place, and even the mental toll of societal pressures can shape our lifespans in ways we might not fully understand.  

These findings align with the United Nations Sustainable Development Goals (SDGs), particularly [Goal 3](https://sdgs.un.org/goals/goal3) (which prioritizes mental health and well-being) and [Goal 10](https://sdgs.un.org/goals/goal10) (aimed at reducing inequalities)—both critical to fostering longer, healthier lives globally. A [2023 Lancet report](https://www.thelancet.com/journals/lanpub/article/PIIS2468-2667(23)00156-9/fulltext) further underscores this link, showing that addressing mental health disparities and social inequities could add years to global life expectancy averages.  

## Life Expectancy at Birth Across the Globe 
To explore the intricate relationship between social factors and life expectancy, we turn to the World Health Organization's [Global Health Estimates (GHE): Life expectancy at birth](https://www.sciencedirect.com/science/article/pii/S0191886920307960). The GHE data has been enriched by combining it with additional indicators from [Human Development reports](https://hdr.undp.org) to create [Life Expectancy at Birth Across the Globe](https://www.kaggle.com/datasets/iamsouravbanerjee/life-expectancy-at-birth-across-the-globe/data) This comprehensive dataset offers insights into life expectancy at birth across 194 countries, including standardized ISO3 country codes and regional groupings by continent.

Looking at the years from **2000-2020**, the data reveals that the global average life expectancy at birth rose from about 66.7 to 71.8 years—an increase of over five years. This two-decade period reflects continuous improvements in healthcare access, disease control, and living standards across the world. However, these trends are not uniform across the globe. In 2020, Monaco topped the charts with an average life expectancy of *86.5 years*. In great contrast, Chad recorded the lowest number at just *52.8 years*—a 34-year gap that shows just how deep and the inequalities in global health really ares. 

### A World Divided by Longevity: How Life Expectancy Varies by Continent
While global life expectancy has steadily increased over the past two decades, not all regions have experienced this equally. The uneven distribution becomes even more evident when analysing continental trends. 
To shed light on this, a dynamic bar chart was created to compare life expectancy across continents over time. 

<iframe src="{{ site.baseurl }}/images/continent_bar_plot.html" width="700" height="550"></iframe>

The data shows a large contrasts—where geography, wealth, and policy shape the length and quality of life in serious ways.

**Europe** and **Oceania** have consistently had the highest average life expectancies. Countries like Monaco, where life expectancy reached 86.5 years in 2020, and Australia, averaging over 83 years, reflect the quality of their healthcare systems, stable government, and comprehensive welfare programs. According to the [World Bank](https://data.worldbank.org/indicator/SP.DYN.LE00.IN), many European nations have had a life expectancy near or above the 80-year mark throughout the 21st century, as a result of their sustained investment in public health and social infrastructure.

In recent years, **Asia** have seen rapid improvements. Over the last two decades, countries like Japan, Singapore, and South Korea have dramatically extended lifespans. The reasoning being their cutting-edge medical care, populations with some of the world’s highest education levels, and public health systems that proactively tackle everything from aging populations to pandemic threats. For instance, South Korea’s average life expectancy rose from around 75.9 years in 2000 to 83.5 years in 2020, placing it among the world’s leaders ([OECD Health Statistics](https://www.oecd.org/health/health-data.htm)).

**North America**, long known for its high life expectancy, experienced a more complex change. While countries like Canada have maintained relatively stable numbers, the United States has seen stagnation—and even slight declines—especially in during the COVID-19 pandemic. In 2020, U.S. life expectancy dropped by nearly 1.8 years, the largest single-year decline since World War II, primarily due to the pandemic and widening health inequities ([CDC](https://www.cdc.gov/nchs/pressroom/nchs_press_releases/2021/202107.htm)).

A big contrast to the other continents is seen in **Africa**, where life expectancy, though still improving, remains significantly lower than in other regions. In 2020, several sub-Saharan nations, including Chad and Nigeria, had an average life expectancy below 60 years. The causes are among many things such as: high rates of infectious disease, maternal and infant mortality, and limited access to quality healthcare. Yet, there are areas of growth as Rwanda and Ethiopia, for example, have made significant improvements, thanks to targeted health programs and international support ([WHO](https://www.who.int/data/gho)).

**Latin America and the Caribbean** presented a mixed picture. Countries like Chile and Costa Rica have life expectancies that are comparable to many high-income nations, often exceeding 80 years. However, the political and economic instability in other parts of the region also means unequal access to healthcare, which causes slower progress or even regressions in countries like Venezuela and Honduras.

While average life expectancy gives a helpful overview, it doesn't show all the nuances within each region. To delve deeper, a **ridgeline plot** was used to visualize the distribution of life expectancy across countries within each continent over time. This not only shows central patterns but also the variations and hidden inequities that the average number often overlook.
![image](/images/ridgelineplot.png) 

The ridgeline plot further reveals differences within continents. In **Africa**, the distribution widened slightly over time, which indicates persistent inequality: while some nations achieved rapid growth in life expectancy, others lagged due to conflict or resource limitations. In contrast, **Europe’s** distributions remained tightly clustered, reflecting consistently high health standards across countries. **Asia’s** ridge lines shifted rightward and narrowed which shows a great improvement throughout the continent as a whole.

These visualizations collectively highlight a dual narrative: while the world has moved forward, it has not done so together. Regional and national differences remain. As the world contiues to work toward the UN’s Sustainable Development Goals, understanding and addressing these differences is more critical than ever.

## 2014, an insightful year

Include worldmap for life expectancy in this year (TODO)

Explain the questionaries and link other datasets

Include world maps for the countries that are common to all datasets in this year and thus it is part of the following results

Add plot for how importance dataset answer are measured (weighted values)

Add correlation plot between all different variables

Add correlation matrix 

### Values and demography discussion

As seen on this [paper](https://www.sciencedirect.com/science/article/pii/S0191886920307960), values are not only culture-wise but also vary with age, thus the age distribution for each country should be considered...


### Can Happiness Predict Longevity? Modeling Life Expectancy with Social Indicators
In an age where global health is shaped by more than just medicine, understanding how social well-being influences longevity is increasingly important. To explore this connection, we developed a prediction model using data from happiness and life satisfaction surveys—two social indicators that showed the strongest linear correlation with life expectancy in preliminary analysis.
FOr the year **2014** we trained a linear regression model to predict life expectancy based on these two key variables.

**Add Actual vs Predicted Life Expectancy (based on social data)**

The model gave an R² score of 0.44, meaning that happiness and life satisfaction explain 44% of the variation in life expectancy across countries. The scatterplot comparing the model’s predictions to actual life expectancy values shows a moderate but clear trend. Countries with higher happiness and life satisfaction tend to experience longer lifespans, suggesting that well-being is more than a side effect of health, but also a contributing factor.

This analysis doesn’t claim causation, it does show evidence that how people feel about their lives can be a meaningful factor of determining their actual health outcomes. In a time where longevity is often seen through economic or technological lenses, taking into account social metrics into global health strategies might give a more holistic, and perhaps also, a more effective path forward.