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

**Finding a single index value for comparison**

\- Density amplifies the effect so there is a squared multiplication effect. (D<sup>2</sup>, where D stands for density )

\- The road network may result in varying proximity even for the same density. For higher the distance lower is the proximity hence inversely proportional to distance (1/d, where d stands for distance)

\- The variability of amenities is a multiplication factor of the effect. However, supportive amenities is a good indicator and others are not. Average sum of count of supportive amenities deducted by average sum of count of non supportive amenities. (Sum(f1/n1+f2/n2+...)-Sum(fo1/no1+fo2/no2+...)) This value can be either positive or negative. This value can be a relatively larger number, hence using the ratio of the value to standard value(described below section) will make the calculation better. (value/standard\_value)

So, the formula will be D<sup>2</sup>/d x (value/standard\_value)


### **Quantified Interaction of Amenities**

**Note**: Choosing the average value as standard value. The next section discusses more about the standards: average or country standard or scientifically proven standard.

|                    |                       |                              |                        |                      |                        |                                    |
| ------------------ | --------------------- | ---------------------------- | ---------------------- | -------------------- | ---------------------- | ---------------------------------- |
| Amenity 1          | Amenity 2             | Life Expectancy(Val. - Avg.) | Education(Val. - Avg.) | Economy(Val. - Avg.) | Happiness(Val. - Avg.) | Positive/Negative Indicator(sum/4) |
| Population density | Schools               | Number                       | Number                 | Number               | Number                 | Sum(Numbers)                       |
| Population density | Public transportation | Number                       | Number                 | Number               | Number                 | Sum(Numbers)                       |
| …                  | …                     | …                            | …                      | …                    | …                      | …                                  |

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

**5. Contextual Considerations**

It's important to note that the impact of amenities collision can be highly context-specific. What is considered a positive or negative effect in one area may not apply to another, depending on the local population's needs, preferences, and the existing infrastructure and services.

In summary, "Amenities Collision" is a concept that considers how the coexistence and interaction of different amenities and infrastructure elements can influence the overall quality of life, well-being, or other relevant factors in a given area. It provides a framework for quantifying these impacts and understanding how they vary across different contexts and geographic regions.
