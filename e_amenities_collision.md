# Amenities Collision
Amenities Collision is a concept that delves into the interaction or intersection of different amenities or infrastructure components within a geographic area and how these interactions can impact the overall quality of life, well-being, or other relevant factors. This note expands on this concept by discussing various aspects related to amenities collision.


### **1. Interaction of Amenities**

Amenities encompass various features or facilities within a community or geographic region that contribute to its livability and desirability. These amenities include healthcare facilities, schools, parks, recreational facilities, public transportation, cultural centers, restaurants, and more.


#### Examples of Interaction of Amenities:

- A school located near a noisy airport or highway
- A hospital located near a polluting factory
- A park located near a busy road
- A residential area located near a commercial area with heavy traffic
- A wetland area located near a development project


#### Negative Effects of Amenities Collision:

- Noise pollution
- Air pollution
- Traffic congestion
- Environmental pollution
- Reduced quality of life
- Increased health risks


#### How to Avoid Amenities Collision with Negative Effects:

- Careful land use planning
- Transportation planning
- Environmental regulations
- Community engagement


### **2. Positive and Negative Effects**

Amenities collision can result in both positive and negative effects, depending on the specific combination of amenities and local circumstances.


#### Positive Amenities Collision:

- Schools near residential areas for improved accessibility
- Proximity of parks and healthcare facilities enhancing well-being


#### Negative Amenities Collision:

1. Noisy industrial zones near residential areas causing pollution
2. Roads with high traffic congestion near schools posing safety risks


### **3. Quantifying Impact**

Quantifying the impact of amenities collision involves representing it as a numerical value on a scale reflecting its effect on factors like life expectancy, education, economy, and happiness. Various methods can be used, such as surveys and data analysis, to measure this impact.

Quantifying the impact of amenities collision can be challenging, but there are a number of methods that can be used. One approach is to use surveys to ask residents and visitors about their experiences. This can help to gather information about the negative effects of amenities collision, such as increased congestion, higher housing costs, and a reduced quality of life.

Another approach is to use data analysis to look at the patterns of development and use of amenities. For example, researchers can look at changes in traffic patterns, property values, and crime rates in areas where amenities are concentrated.


#### Examples of Quantified Impact:

- A study by the University of California, Berkeley found that a 10% increase in the number of restaurants in a neighborhood led to a 1.2% increase in traffic congestion.
- A study by the University of Chicago found that a 10% increase in the number of tourists in a city led to a 0.5% increase in crime.
- A study by the University of Massachusetts Boston found that a 10% increase in the number of Airbnb listings in a neighborhood led to a 1% increase in rent.


### **General Interaction of Amenities**

|                    |                       |                     |               |             |               |                                 |
| ------------------ | --------------------- | ------------------- | ------------- | ----------- | ------------- | ------------------------------- |
| **Amenity 1**      | **Amenity 2**         | **Life Expectancy** | **Education** | **Economy** | **Happiness** | **Positive/Negative Indicator** |
| Population density | Schools               | Negative            | Negative      | Positive    | Negative      | Negative                        |
| Population density | Public transportation | Positive            | Positive      | Positive    | Neutral       | Neutral                         |
| …                  | …                     | …                   | …             | …           | …             | …                               |


### **Using OSM Data for Comparative Analysis on Collision**

**Use OSM data to calculate the following:**

\- Density of amenities: This is the number of amenities per unit area. You could calculate the density of all amenities, or of specific types of amenities, such as restaurants, bars, or shops.

\- Proximity to amenities: This is the average distance from a point to the nearest amenity. You could calculate the proximity to all amenities, or to specific types of amenities.

\- Mix of amenities: This is the variety of amenities that are available in an area. You could calculate the mix of amenities using a diversity index, such as the Shannon index.

**Quantify amenities collision using OSM data**

\- Identify the amenities and fetch their data.

\- Calculate the density, proximity, and mix of amenities for the area of interest.

\- Compare these metrics to other areas to see how the area of interest compares.


### **Quantified Interaction of Amenities**

**Note**: Choosing the average value as standard value. The next document discusses more about the standards: average or country standard or scientifically proven standard.

**Finding Proper Index to Represent Collision and Resulting Intensity**

To encapsulate the collision and its resulting intensity, we need a comprehensive index. This index reflects both the impact of an amenity's interaction with others and the density of the area. The process involves several steps:

1.  Create a table of indicators with the first column representing the core amenity with which other amenities interact. The second column lists the interacting amenities. The third column indicates the effect, either positive (+1) or negative (-1), of the interacting amenity. The fourth column contains the effect scale, ranging from 0 to 100, signifying the magnitude of the interaction's impact.
    
2.  Calculate the average distance, used as a proximity indicator, within the selected region using the formula: "avg. distance = square root of (area of selected region / number of items)."
    
3.  To determine the interaction value of other amenities with the chosen amenity, employ the formula: "Interaction Value of Other Amenities = Sum(E * S * AVDs / AVDi) / n;"
    
    -   E represents the effect of an amenity over the chosen amenity.
    -   S signifies the scale of the interaction, ranging from 0 to 100.
    -   AVDs represents the average distance (driven by density) of the selected item.
    -   AVDi represents the average distance (driven by density) of the interacting amenity.
    -   Finally, sum the results and divide by the number of interacting amenities. Let's call this value "value_amenity."
4.  Value_amenity offers insights into the interaction of a single amenity, providing information about its impact. The next step is to assess the impact on the selected region as a whole.
    
5.  To gauge the region's overall impact, calculate the value_amenity for all related amenities within the area related to the case study. Sum these values and then divide by the total number of amenities, yielding "aggregated_value_amenities."
    
6.  Both value_amenity and aggregated_value_amenities fluctuate within the range of -100 to 100. To gain a deeper understanding of the interaction's intensity, multiply these values by density: "density = (total items of all amenities / area)."
    

This refined approach provides a holistic representation of amenities collision and its intensity, facilitating more insightful comparisons.

**For working on several theme**

If we plan to use average (Avg) as an standard:

|                    |                       |                              |                        |                      |                        |                                    |
| ------------------ | --------------------- | ---------------------------- | ---------------------- | -------------------- | ---------------------- | ---------------------------------- |
| Amenity 1          | Amenity 2             | Life Expectancy(Val. - Avg.) | Education(Val. - Avg.) | Economy(Val. - Avg.) | Happiness(Val. - Avg.) | Positive/Negative Indicator(sum/4) |
| Population density | Schools               | Number                       | Number                 | Number               | Number                 | Sum(Numbers)/4                       |
| Population density | Public transportation | Number                       | Number                 | Number               | Number                 | Sum(Numbers)/4                     |
| …                  | …                     | …                            | …                      | …                    | …                      | …                                  |


Based on how large the numbers are, a range should be defined for positive, negative and neutral or on a scale ranging from 0 to n for both positive and negative number. Any of these approach are to be chosen based on the targeted achievement

Here are some additional references on this topic:

- [Gentrification and Neighborhood Revitalization](https://nlihc.org/resource/gentrification-and-neighborhood-revitalization-whats-difference) by the National Low Income Housing Coalition
- [The Price Of Popularity: The Impact Of Overtourism On Destinations](https://givinggetaway.com/the-impact-of-overtourism-on-destinations/#:~:text=Overtourism%20occurs%20when%20a%20destination,erosion%2C%20and%20other%20negative%20impacts)



### **4. Threshold**

The text also mentions that this scale has a threshold. This means that there may be a limit or a point beyond which the impact of amenities collision does not increase or decrease further. In other words, there may be a maximum positive or negative effect that can be achieved by a particular combination of amenities.

This is a complex concept, and there is no single, agreed-upon definition. However, some possible definitions include:

\- The point at which the negative impacts of amenities collision outweigh the positive impacts.

\- The point at which the cost of mitigating the negative impacts of amenities collision becomes too high.

\- The point at which the quality of life in an area becomes significantly reduced due to amenities collision.

It is important to note that the threshold of amenities collision is not a fixed point. It can change over time as the community changes. For example, a community may be able to tolerate a higher level of amenities collision as its population grows and its economy strengthens.

### **5. Contextual Considerations**

It's important to note that the impact of amenities collision can be highly context-specific. What is considered a positive or negative effect in one area may not apply to another, depending on the local population's needs, preferences, and the existing infrastructure and services.

In summary, "Amenities Collision" is a concept that considers how the coexistence and interaction of different amenities and infrastructure elements can influence the overall quality of life, well-being, or other relevant factors in a given area. It provides a framework for quantifying these impacts and understanding how they vary across different contexts and geographic regions.
