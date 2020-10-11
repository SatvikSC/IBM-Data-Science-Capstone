**1. Clearly define a problem or an idea of your choice. Remember that data science problems always target an audience and are meant to help a group of stakeholders \
solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.**

ANS:Road accidents are extremely common. Often times they lead to a loss of property and even life. Wouldn’t it be great to be able to understand what are the most common causes, \
in order to prevent them from happening? With this analysis, I am attempting to understand these factors and their correlation. This analysis has multiple applications \
like an app that will prompt the drivers to be more careful depending on the weather and road conditions on any given day or a way for the police to enforce more safety \
protocols. In this instance, I am using the data from the City of Seattle’s police department showing all the collisions from 2004 till present.


**2. Describe the data that you will be using to solve the problem or execute your idea. So make sure that you provide adequate explanation and discussion, 
with examples, of the data that you will be using.**

ANS: There are 194,673 observations and 38 variables in this data set. Since we would like to identify the factors that cause the accident and the level of severity, \
we will use SEVERITYCODE as our dependent variable Y, and try different combinations of independent variables X to get the result. Since the observations are quite large, \
we may need to filter out the missing value and delete the unrelated columns first. Then we can select the factor which may have more impact on the accidents, \
such as address type, weather, road condition, and light condition.

The target Data to be predicted under (SEVERITYCODE 1-prop damage 2-injury) label.
Other important variables include:
• ADDRTYPE: Collision address type: Alley, Block, Intersection
• LOCATION: Description of the general location of the collision
• PERSONCOUNT: The total number of people involved in the collision helps identify severity involved
• PEDCOUNT: The number of pedestrians involved in the collision helps identify severity involved
• PEDCYLCOUNT: The number of bicycles involved in the collision helps identify severity involved
• VEHCOUNT: The number of vehicles involved in the collision identify severity involved
• JUNCTIONTYPE: Category of junction at which collision took place helps identify where most collisions occur
• WEATHER: A description of the weather conditions during the time of the collision
• ROADCOND: The condition of the road during the collision
• LIGHTCOND: The light conditions during the collision
• SPEEDING: Whether or not speeding was a factor in the collision (Y/N)
• SEGLANEKEY: A key for the lane segment in which the collision occurred
• CROSSWALKKEY: A key for the crosswalk at which the collision occurred
• HITPARKEDCAR: Whether or not the collision involved hitting a parked car
