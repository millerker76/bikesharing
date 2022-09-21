
# $\textcolor{blue}{\text{NYC CitiBike - Trip Analysis}}$   <img src="https://user-images.githubusercontent.com/107505166/191397468-04815154-11ff-46c0-8030-cc5eff50b154.png" width = "280" height = "140" > 

<img src="https://user-images.githubusercontent.com/107505166/191382719-f842b7f1-0274-4e24-a322-1598a4108065.PNG" width="400" height="400"> 



## Overview of the Project:
The purpose of this project, using a large data set from the successful 10-year old New York City CitiBike bike sharing program, is to analyze CitiBike trip data and extract useful insights for a client who is exploring starting a bike sharing program in Des Moines, Iowa.  
## Try out the multi-criteria search filter
<b> Follow these steps to practice using the search filters:</b> 

1.  Enter a state (try <b> ca </b> for California as in the example below) and notice that the table to the right is now filtered to only display sightings in California.  $\textcolor{blue}{\text{ (figure a)}}$ 
2.  Experiment with further filtering the results by entering <b> el cajon  </b>  to show only results for El Cajon, California.   $\textcolor{blue}{\text{ (figure b)}}$ 
3.  You can continue to further filter results by date, shape, etc. or start over with new criteria. 

$\textcolor{blue}{\text{ (figure a)}}$ 
![Capture2](https://user-images.githubusercontent.com/107505166/188705533-81e92a2c-28e3-466b-ace7-c5144b521a9a.PNG)

$\textcolor{blue}{\text{ (figure b)}}$ 
![Capture3](https://user-images.githubusercontent.com/107505166/188705546-a7b27737-231a-4b54-8ff8-86fc82d1abbf.PNG)

 
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
