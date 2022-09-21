
# $\textcolor{blue}{\text{NYC CitiBike - Trip Analysis}}$  
<img src="https://user-images.githubusercontent.com/107505166/191382719-f842b7f1-0274-4e24-a322-1598a4108065.PNG" width="400" height="400"> 

## Overview of the Project:
The purpose of this project, using a large data set from the successful 10-year old New York City CitiBike bike sharing program, is to analyze CitiBike trip data and extract useful insights for a client who is exploring starting a bike sharing program in Des Moines, Iowa.   

All the visualizations for this project can be seen on Tableau Public:   https://public.tableau.com/views/NYCitiBikeTripAnalysis/NYCitibikeTripAnalysis?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link  

## Insights about CitiBike trips.    
<b> 1. Trip duration:</b>   
###      $\textcolor{blue}{\text{Short trips}}$  
This visualization plots unique bike trips by the length of time the bike was checked out.  We can see that customers are using CitiBikes for bike trips  $\textcolor{blue}{\text {under 20 minutes}}$ 
![Trip Duration all users](https://user-images.githubusercontent.com/107505166/191627672-d0829bd3-eb2b-41a9-8095-eb663108df86.PNG)

This visualization plots unique bike trips by the length of time the bike was checked out $\textcolor{blue}{\text {and by gender. }}$   For all users, regardless of gender, customers are using CitiBikes for bike trips  $\textcolor{blue}{\text {under 20 miutes}}$  
![Trip duration](https://user-images.githubusercontent.com/107505166/191400549-50eff202-70f6-401e-a6a5-48a37c65ccac.PNG)


<b> 2. Usage by gender: </b>   
### $\textcolor{blue}{\text{More bike usage by males}}$  
In this visualization, unique bike trips are charted by the gender of the user.  Male users account for nearly $\textcolor{blue}{\text {two-thirds}}$  of all trips.  

<img src="https://user-images.githubusercontent.com/107505166/191404225-40fefa48-899b-43c0-b6b5-a5bfe86e23fa.PNG" width="600" height="300">

<b>   </b>  
<b>   </b> 
<b> 3. Usage trends per time of day and day of the week: </b> 
### $\textcolor{blue}{\text{Peak usage is during typical commuting hours and on weekends}}$  
This heat map visualization shows areas of concentrated bike usage by hour of day and day of week.  We can see that usage is generally heaviest during weekday morning and late afternoon hours in a pattern that correlates with typical commuter patterns, with the second heaviest concentration on weekends.   Usage on Wednesday afternoons need further exploration!  

![Heat map2](https://user-images.githubusercontent.com/107505166/191406526-73bdd1ec-aefe-4864-bc54-fa47a917ca1a.PNG)

<b>   </b>  
<b>   </b> 
<b> 4. Customer type as factor in usage </b> 
### $\textcolor{blue}{\text{Subscribers rule!}}$  
Over $\textcolor{blue}{\text {Eighty percent}}$ of CitiBike trips are taken by subscribers

<img src="https://user-images.githubusercontent.com/107505166/191409125-92c87bd0-6859-48e3-accf-8d6e9d066ef7.PNG" width="600" height="300">

#### Summary of findings 
* There are multiple input boxes to allow entering multiple filter criteria, but there is no "clear filter" button, so it's a little awkward to have to manually clear the text entered when ready to enter new filter criteria.
* I've added boilerplate text next to the input boxes to instruct users on how to enter the text data (it needs to be in lower case for the filter to "find" it), but this isn't very elegant.  It would be best to update the javascript filter to be case-insensitive.
* It could be very frustrating to search for the shape filter without knowing which shapes have been stored in the data set.   It would be helpful for the "shape" input filter box to be a drop-down box populated with all the available shapes.
 
$\textcolor{blue}{\text{ (Recommended for Further Analysis)}}$ 
| -----------------------------------------------------------------------------|                                            
| Add clear filter button                                                      |
| Update javascript filter function to be case-insensitive                     | 
| Add populated drop-down boxes for Country, State/Province and Sighting shape |
