# 🚲 CitiBike Data Visualization 🚲
### Tableau public link below
[Tableau](https://public.tableau.com/app/profile/jonathan.fuentes/viz/Challenge_16212243168080/NYCBikeData) 🔗

- Utilizing data provided by CitiBike for and Tableau I created a Viz for checkout times for users. Utiliziing Tableau and filtering the data I was able to create a visual to show the checkout times for all users with a filter on the right right side that allows the user to select filters. Before being able to do this we needed to convert values with the data to allow us to use them in Tabluew. The original data showed "tripduration" in seconds and they neede to be converted into a 'timestamp". 

### DataFrame without the 'tripduration' converted 

![](https://github.com/fuentesjo6/bikesharing/blob/main/Resources/df_w:out_conversion.png)


### DataFrame with 'tripduration' converted to "timestamp'

![](https://github.com/fuentesjo6/bikesharing/blob/main/Resources/df_with_conversion.png)

- Utlizing the same data and filtering using Tableau I created a visualization of "User Trips by Gender". This visual shows a heat mat of "Customer" and "Subscribers", we can then see that male subscribers tend to utilze the bicycles more than female subscribers do. The visual also allows you to see that what days of the week have the heaviest usgae of bikes. 

![](https://github.com/fuentesjo6/bikesharing/blob/main/Resources/User_trips_by_gender_by_weekday.png)

- The below visual shows us the trips by week per hour in the form of a heat map. Based on the heat map we can see that the busiest times of the week are before and after typical work hors. 

![](https://github.com/fuentesjo6/bikesharing/blob/main/Resources/Trips_by_weekday_per_hour.png)

## Final Presentation 

- From the data we were presented with and the ulitization of Tableau to create visuals we are able to see:
  - Checkout times for users, this visual gives us an opportunity to see what peak times are.
  - We were able to see there are more male users than female users.
  - You can also see that subscribers utilize their bikes 🚲 more than customers so they take full advantage of their subscription. 
## Suggestions
 - I created a visual for the bike locations that are used the most to give us a visual of where more maintenance needs to be completed on the bikes or perhaps even replacing the bikes based on usage. The sheet is called "Top Bike Stations and Bike Usage", this will allow you to see what bike ID has been used the most along with the locations that have the most rented bikes. This link will take you straight to the Tableau visual. 🔗 [Tableau](https://public.tableau.com/app/profile/jonathan.fuentes/viz/Challenge_16212243168080/NYCBikeData) 🔗
 - I was also able to put together another visual allowing the user to see the "Top Bike Stattion by Gender". Having this information will help make marketing decisions on how to target a specific gender to increase overall subscriptions. 

