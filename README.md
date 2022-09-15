# 
Tableau

# NYC Bike Sharing Analysis
## Overview of the statistical analysis:
We are looking to  convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, we will be presenting a Tableau story to the key stakeholders who would like to see a bike trip analysis. We are going to focus our analysis using New York City data and showcase it's top starting and ending locations, which times are busiest and what the user demographic looks like. While Des Moines, Iowa is an extremely different city, learning what works in NYC and applying it to Des Moines will improve our chances of having a successful rideshare business. 

### Results:

<img src="https://user-images.githubusercontent.com/107224632/190511964-15cc2546-7bc1-41d7-a547-95a44139e3fa.png" width=80% height=80%><br />
*Figure 1: Tableau Story, story point: Top Starting Locations*<br />

In reviewing the top staring locations visualization, we can see that the heaviest usage for starting locations feature in lower to mid Manhattan. This was done by using Tableau's "map" mark as well as the start station longitude and latitude from the NYC ride share data. By having Tableau show the populatity of a starting location by the size and shade of the dot, we can easily see the areas that are most popular. This visualization shows us that we need to pinpoint Des Moines' culture centers and/or tourist locations as lower and mid Manhattan are famous for the artsy Greenwich Village, hip Tribeca, vibrant Chinatown, and the buzzing Financial District. It’s also home to the Whitney Museum of American Art, along with One World Trade Center and the 9/11 Memorial & Museum. If we can point these Des Moines locations to place our rideshare bikes, we can replicate a simliar success to the NYC rideshare program.

<img src="https://user-images.githubusercontent.com/107224632/190511975-3f734913-83f5-403d-8c36-eef3cb316b5a.png" width=80% height=80%><br />

*Figure 2: Tableau Story, story point: Top Ending Locations*<br />
To support our analysis of figure 1, we see that the Top Ending Locations visualization also has riders ending their trips more often than not in lower or mid Manhattan. This visualization was created in the same way as figure 1, except we used teh end station longitude and latidtude date points. The similar maps for the start and end trip locations stresses the importance for needing to identify cultural and/or tourist locations in Des Moines for our rideshare bicycles. A importance difference we see in the ending locations visualization is that while the rides did end in the same general area as the starting locations, the ending locations were much more concetrated to lower Manhattan. This supports the idea, that we may need to ensure that our prime locations in Des Moines not only have enough bikes to share, but also extra spaces to recieve new bikes that came from other stations. 

<img src="https://user-images.githubusercontent.com/107224632/190511989-e67b4238-3100-495e-9e7f-b28072158642.png" width=80% height=80%><br />
*Figure 3: Tableau Story, story point: Checkout TIme for Users*<br />

In this visualization, we have a line graph that shows the most popular length of a bike checkout is in hours. As we can see in the graph, the most common length of checkout in NYC was less than 20 minutes. In reviewing this data, we can begin to estimate that it may be important to structure our prices around 5 minute or so increments versus charging by distance traveled. This would also make it customer friendly since it is easier to keep track of time than miles traveled. 

<img src="https://user-images.githubusercontent.com/107224632/190511998-cf3331d0-118c-4e6a-8424-32c0d243b3cc.png" width=80% height=80%><br />
*Figure 4: Tableau Story, story point: Weekday for each hour*<br />

In this visualization, we have a heat map that shows the most popular time during the week is concetrated during the morning and afternoon hours of 8-9am and 4-6pm with the business day being Thursday. Weekends are busy but the rides are much more spread out, which is evident by the semi dark orange shading between the hours of 9am and 6pm with Saturday being the slightly more busy day. When applying this data to setting up our Des Moines rideshare, we see that our bike maintanence and repair would best be done outside of the hours from 9am-6pm. Since we see that the bikes are used during the week, it would be important to schedule maintance and repair outside of peak hours and not on the busiest days. 

<img src="https://user-images.githubusercontent.com/107224632/190512008-ccafcca8-3d4a-4f35-8eb8-28a0ba8c09e1.png" width=80% height=80%><br />
*Figure 5: Ta4bleau Story, story point: Checkout times by gender*<br />

In this visualization, we have a line graph simlar to what was present in figure #3. This graph however shows the same breakdown higlighting the length of time for each gender. We can see that self identified males are the most popular users of the rideshare program in NYC. Despite being less popular with users who identify as female, both male and female users share the similar checkout times. Unidentified users buck the trend, having much longer rides than gender identifying users. This line graph can assist our Des Moines rideshare marketing to skew torwards a male audeince since they appear to be the most popular user. 

<img src="https://user-images.githubusercontent.com/107224632/190512014-dfee21ef-1ae6-48f6-b205-496cba113c4a.png" width=80% height=80%><br />
*Figure 6: Tableau Story, story point: Weekday for each hour*<br />

In this visualization, we have a heatmap similar to what was shown in figure 4. The difference is that this heat map breaks down the user trips by gender. We can see that self identified males are still the most popular users of the rideshare program in NYC and are more likely to use the program during the week. Despite being less popular with users who identify as female, they share the similar checkout hours. This heatmap can again assist our Des Moines rideshare marketing to skew torwards a male audeince, but show more male driven ads during the days they are most active on the bikeshare service. 

<img src="https://user-images.githubusercontent.com/107224632/190512024-077eae7d-c734-47f4-8499-c8b11b578d81.png" width=80% height=80%><br />
*Figure 7: Tableau Story, story point: User Trips by Gender by Weekday*<br />

Rounding out our visualizations, we have a heatmap that also depicts user usage during the week by gender, however, it focuses on what type of user they are, a customer or subscriber. We can observe that self identified males are more likely to be a subscriber than females and are more active during the week. This heatmap can again assist our Des Moines rideshare marketing to focus on pushing our subscriptions to female and unknown gender customers.

### Summary





For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

Show the length of time that bikes are checked out for all riders and genders
Show the number of bike trips for all riders and genders for each hour of each day of the week
Show the number of bike trips for each type of user and gender for each day of the week.
Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.
