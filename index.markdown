---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
title: Home
---
# Global Life Expectancy: What Social Factors Reveal About Our Lifespan
_By Cecilie Mai Do & Laura Pascual Hebrero_  

![image](/images/front-picture.jpg)

When we think about life expectancy, we often focus on factors like healthcare access, diet, and genetics. But what if the secret to a longer life lies not in our physical bodies, but in the social forces around us? Recent studies suggest that the quality of our relationships, our mental health, and the social structures we navigate also play an important role in determining how long we live. The connections we maintain with family and friends, the support systems we have in place, and even the mental toll of societal pressures can shape our lifespans in ways we might not fully understand.

Mental health issues such as depression, anxiety, and stress can be just as detrimental to our life expectancy as physical illness, while a lack of social support or the prevalence of suicide rates in certain regions can be direct indicators of how social environments influence longevity. These hidden factors—often overlooked in traditional healthcare discussions—could be critical pieces of the puzzle when it comes to understanding life expectancy across different populations.

This article will explore weather social factors, from mental health challenges to the importance of social connections, impact life expectancy worldwide. By examining the data and digging deeper into the ways our society affects our lifespan, we can gain a clearer picture of what really keeps us alive—and why some of us don't make it as long as others.

## Life Expectancy at Birth Across the Globe 
To explore the intricate relationship between social factors and life expectancy, we turn to the World Health Organization's [Global Health Estimates (GHE): Life expectancy at birth](https://www.sciencedirect.com/science/article/pii/S0191886920307960). The GHE data has been enriched by combining it with additional indicators from [Human Development reports](https://hdr.undp.org) to create [Life Expectancy at Birth Across the Globe](https://www.kaggle.com/datasets/iamsouravbanerjee/life-expectancy-at-birth-across-the-globe/data) This comprehensive dataset offers insights into life expectancy at birth across 194 countries, including standardized ISO3 country codes and regional groupings by continent.

Looking at the years from **2000-2020**, the data reveals that the global average life expectancy at birth rose from about 66.7 to 71.8 years—an increase of over five years. This two-decade period reflects sustained improvements in healthcare access, disease control, and living standards across much of the world. However, these trends are not uniform across the globe. In 2020, Monaco once again topped the charts with an average life expectancy of *86.5 years*. In great contrast, Chad recorded the lowest figure at just *52.8 years*—a 34-year gap that highlights the deep and persistent inequalities in global health outcomes. 


### A World Divided by Longevity: How Life Expectancy Varies by Continent
While global life expectancy has steadily increased over the past two decades, not all regions have shared equally in this progress. The uneven distribution becomes even more evident when analysing continental trends. 
To shed light on these disparities, a dynamic bar chart was created to compare life expectancy across continents over time. 

<iframe src="{{ site.baseurl }}/images/continent_bar_plot.html" width="700" height="550"></iframe>

The data shows a stark contrasts—where geography, wealth, and policy shape the length and quality of life in profound ways.

**Europe** and **Oceania** have consistently recorded the highest average life expectancies. Countries like **Monaco**, where life expectancy reached **86.5 years** in 2020, and **Australia**, averaging over **83 years**, reflect the strength of their healthcare systems, stable governance, and comprehensive welfare programs. According to the [World Bank](https://data.worldbank.org/indicator/SP.DYN.LE00.IN), many European nations have hovered near or above the 80-year mark throughout the 21st century, a testament to sustained investment in public health and social infrastructure.

In contrast, **Asia** has emerged as a region of rapid improvement. Over the last two decades, countries such as **Japan**, **Singapore**, and **South Korea** have seen life expectancy climb sharply, bolstered by robust healthcare systems, high educational attainment, and innovative public health strategies. For instance, South Korea’s average life expectancy rose from around **75.9 years in 2000 to 83.5 years in 2020**, placing it among the world’s leaders ([OECD Health Statistics](https://www.oecd.org/health/health-data.htm)).

**North America**, long known for its high life expectancy, experienced a more complex trajectory. While countries like **Canada** have maintained relatively stable outcomes, the **United States** has seen stagnation—and even slight declines—especially in the wake of the **COVID-19 pandemic**. In 2020, U.S. life expectancy dropped by nearly **1.8 years**, the largest single-year decline since World War II, primarily due to the pandemic and widening health inequities ([CDC](https://www.cdc.gov/nchs/pressroom/nchs_press_releases/2021/202107.htm)).

The story is more sobering in **Africa**, where life expectancy, though steadily improving, remains significantly lower than in other regions. In 2020, several sub-Saharan nations, including **Chad** and **Nigeria**, reported average life expectancies below **60 years**. The causes are multifaceted: high rates of infectious disease, maternal and infant mortality, and limited access to quality healthcare remain formidable barriers. Yet, there are bright spots—**Rwanda** and **Ethiopia**, for example, have made commendable strides, thanks in part to targeted health programs and international support ([WHO](https://www.who.int/data/gho)).

**Latin America and the Caribbean** presented a mixed picture. Countries like **Chile** and **Costa Rica** boast life expectancies comparable to many high-income nations, often exceeding **80 years**. However, political and economic instability in other parts of the region has led to unequal access to care, causing slower progress or even regressions in countries like Venezuela and Honduras.


While average life expectancy offers a helpful overview, it can obscure the nuances within each region. To delve deeper, a **ridgeline plot** was used to visualize the distribution of life expectancy across countries within each continent over time. This approach not only highlights the central trends but also exposes the spread and internal disparities that averages alone fail to capture.

![image](/images/ridgelineplot.png) 

The ridgeline plot further reveals disparities within continents. In **Africa**, the distribution widened slightly over time, indicating persistent inequality: while some nations achieved rapid gains, others lagged due to conflict or resource limitations. In contrast, **Europe’s** distributions remained tightly clustered, reflecting consistently high standards across countries. **Asia’s** ridge lines shifted rightward and narrowed, suggesting not only overall improvement but also reduced intra-continental disparities, likely due to rapid development in populous nations like **China** and **India**.

These visualizations collectively highlight a dual narrative: while the world has moved forward, it has not done so together. Regional and national disparities remain deeply entrenched. As the global community works toward the **UN’s Sustainable Development Goals**, especially **Goal 3: Good Health and Well-being**, understanding and addressing these differences is more critical than ever.

## 2014, an insightful year

Include worldmap for life expectancy in this year (TODO)

Explain the questionaries and link other datasets

Include world maps for the countries that are common to all datasets in this year and thus it is part of the following results

Add plot for how importance dataset answer are measured (weighted values)

Add correlation plot between all different variables

Add correlation matrix 

Add Actual vs Predicted Life Expectancy (based on social data)

### Values and demography discussion

As seen on this [paper](https://www.sciencedirect.com/science/article/pii/S0191886920307960), values are not only culture-wise but also vary with age, thus the age distribution for each country should be considered...