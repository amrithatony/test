# Test
##project
######yes  an <h1>
*This text will be italic*
**This text will be bold**
_You **can** combine them_
* Item 1
* Item 2
  * Item 2a
  * Item 2b
  
  1. Item 1
2. Item 2
3. Item 3
   * Item 3a
   * Item 3b
   
   ![GitHub Logo](/images/logo.png)
   
   ![GitHub Logo](/images/logo.png)
   
   http://github.com - automatic!
[GitHub](http://github.com)



As Kanye West said:

> We're living the future so
> the present is our past.

I think you should use an
`<addr>` element here instead.

tables

First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


#Weather Data Generator
#####Geographical Area under consideration 
Indian subcontinent - mainly India and Sri Lanka.
Size of area considered will be approximately half the size of Australia.
#####Factors influencing the climate of area considered
Indian subcontinent is surrounded by Indian ocean and it has Western Ghats(mountain) and Himalayas. Due to this geographical positioning, proximity to ocean and the topology varaiations, two monsoon monsoon seasons - 
Southwest monsoon and Northeast monsoon occur. These monsoons are the main dynamic factor incfluencing the climate of Indian subcontinent.
##Approaches considered for solving the problem
###Approach 1 - Based on historical data
Retrieve the historical weather data of past 10 years from a reliable source for the selected weather stations. 
Derive a regression equation based on the history data and predict the current value

######Pros:
* Easy to implement
* Better accuracy

######Cons:
* As the problem statement clearly mention to consider geographic,topographic,oceanographic factors,the assumption is that this is **not** the expected approach for problem resolution
* The model will not incorporate the requirements of considering the dynamic factors which evolves over time


###Approach 2 - Mathematical modelling of weather data

Mathematical modellling of the parameters affecting weather is created. Influence of both static parameters(topography, geography, proximity to sea etc.) and dynamic parameters(monsoon clouds from Indian ocean, cold waves from central Asia) are included in the model.

###Approach 3 - 
This approach is a combination of approach 1 and 2. As the mathematical modelling of cloud movement will take multiple days for implementation,the probability of clouds in different stations are configured, based on the movement pattern of monsoon clouds. For example, in Kochi the monsoon clouds will be present during the months June - September, so the probability of clouds in Kochi can be configured between 0.75 to 1 during these months and 0 to 0.5 during other months.

and north east monsoon clouds will be there present during months October-November. 

Monthly average minimum and monthly average maximum of temperature, pressure, relative humidity for different weather stations are retrieved from reliable sources. 
A linear equation is derived 

Pressure is inversely 





