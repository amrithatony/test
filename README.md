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
###Approach 1
Retrieve the historical weather data of past 10 years from a reliable source for the selected weather stations. 
Create linear regression model for continuous variables like temperature, pressure, relative humidity based on the historical data and 
logistic regression for categorical variables like conditions(snowy, cloudy, rainy, sunny).We will be able to generate test data for any 
year using this model.
######Pros:
* Simple method
* Less time involved for implemeting the model
--######Cons:
* The model will not incorporate the requirements of considering geographic,topographic,oceanographic factors 
* The model will not incorporate the requirements of considering the dynamic factors which evolves over time
######Conclusion: 
This is not the expected approach for the problem statement.







