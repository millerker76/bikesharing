
# $\textcolor{blue}{\text{NYC CitiBike - Trip Analysis}}$  
<img src="https://user-images.githubusercontent.com/107505166/191382719-f842b7f1-0274-4e24-a322-1598a4108065.PNG" width="400" height="400"> 

## Overview of the Project:
The purpose of this project, using a large data set from the successful 10-year old New York City CitiBike bike sharing program, is to analyze CitiBike trip data and extract useful insights for a client who is exploring starting a bike sharing program in Des Moines, Iowa. 

## Insights about CitiBike trips.    
<b> 1. Trip duration:</b>   
###      $\textcolor{blue}{\text{Short trips}}$  
For all users, regardless of gender, customers are using CitiBikes for bike trips  $\textcolor{blue}{\text {under 20 miutes}}$ 
![Trip duration](https://user-images.githubusercontent.com/107505166/191400549-50eff202-70f6-401e-a6a5-48a37c65ccac.PNG)

<b> 2. Gender as a factor in usage </b> 
### $\textcolor{blue}{\text{Majority of users are male subscribers}}$  
$\textcolor{blue}{\text{ (figure a)}}$ 
<img src="https://user-images.githubusercontent.com/107505166/191404225-40fefa48-899b-43c0-b6b5-a5bfe86e23fa.PNG" width="300" height="150"> 

![UsersByGender](https://user-images.githubusercontent.com/107505166/191404225-40fefa48-899b-43c0-b6b5-a5bfe86e23fa.PNG)

$\textcolor{blue}{\text{ (figure b)}}$ 


 
## Summary

#### Drawbacks of the new design
* There are multiple input boxes to allow entering multiple filter criteria, but there is no "clear filter" button, so it's a little awkward to have to manually clear the text entered when ready to enter new filter criteria.
* I've added boilerplate text next to the input boxes to instruct users on how to enter the text data (it needs to be in lower case for the filter to "find" it), but this isn't very elegant.  It would be best to update the javascript filter to be case-insensitive.
* It could be very frustrating to search for the shape filter without knowing which shapes have been stored in the data set.   It would be helpful for the "shape" input filter box to be a drop-down box populated with all the available shapes.
 
$\textcolor{blue}{\text{ (Recommended for Future Development)}}$ 
| -----------------------------------------------------------------------------|                                            
| Add clear filter button                                                      |
| Update javascript filter function to be case-insensitive                     | 
| Add populated drop-down boxes for Country, State/Province and Sighting shape |
