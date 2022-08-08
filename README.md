# Bikesharing

WHY WONT THIS UPDATE ON GIT HUB?

# Bikesharing Data Analysis

tableau public project for data bike sharing

## Background

The purpose of this exerize is to demonstrate how to utilize Tableau Public - Data Visualization through worksheets, dashboards and stories

### - For deliverable 1 the purpose is to demonstrate

how the column that included the "tripduration" can be successful convereted to the correct "datetime data type with corrrect formating and exported to a new file.

### - For deliverable 2 the purpsoe is to use Tableau to create visualizations that show:

- How long bikes are checked out for all riders and genders.
- How many trips are taken by the hour for each day of the week, for all riders and genders.
- A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.

### - For deliverable 3 the purpose is to demonstate Tableau's Story feature usings story points as a final presentation.

## Deliverable 1: Change Trip Duration to a Datetime Format

![TripDurationValues_to_Datetime_Format.PNG](/TripDurationValues_to_Datetime_Format.PNG)

## Deliverable 2: Create Visualizations for the Trip Analysis

### - Checkout Times for Users Viz: Line Graph Number of Bikes Checked out of duration per Gender and/or per hour

![Vis1.PNG](/Vis1.PNG)

### Results:
- Amongst all users the most frequent trip duration is five minuets with a count of 146,752 users. 
- The data is right skewed, with most of the users having a trip duration under 25 minuets.
- Almost all the data is under an hour, with posible outliers that should be considered
### - Checkout Times by Gender Viz: Line Graph Number of Bikes Checked out by duration filtered by gender and/or hour

![Vis2.PNG](/Vis2.PNG)

### Results:
- There are more male users than female useres
- Males most frequent trip duration is 5 minuets.
- Females most frequest trip duration is 6 minuets.
- Males indicate the have longer trips, this may be due just to the volume of male vs. female users alone.


### - Trips by Weekday per Hour Viz: A heatmap showing the number of bike trips for each hour of each day of the week

![Viz3.PNG](/Viz3.PNG)

### Results:
- There apears to be a few general patterns:
- On weekdays bikes are in use from 6 a.m. - 10:00 a.m. they increase each hour peaking during the 8:00 a.m. - 9:00 a.m. time slot.  
- On weekdays bikes are also in higher use from 3:00 p.m. to 9:00 p.m. with the exception of Wensdays which indicate moderate use for that days peak hours, but significantly lower compared to other weekdays.
- An assumption would be that users are utilizing the times to get to and from work.
- Weekends (10,000 users or more) to to start later between 8:00 a.m. and 9:00 a.m. and taper down between 9:00 p.m. and 11:00 p.m. Time are in order for Saturday to Sunday.
- This is likely do to leasure activity


### - Trips by Gender (Weekday per Hour): A heatmap showing the number of bike trips by gender for each hour of each day of the week, filtered by gendered

![Viz4.PNG](/Viz4.PNG)

### Results:
- Both genders seem to follow the same general trends
- It might be worth further invesigation to see proportionatl how male and female differ
- It might be worth looking into further the difference between weekday and weekend numbers by women vs. weekday and weekend numbers for men.

### - User Trips by Gender (by Weekday) Viz: A heatmap showing the number of bike trips for each type of user and gender for each day of the week, filterable by user and gender

![Viz5.PNG](/Viz5.PNG)

### Results:

## Deliverable 3: Create a Story and Report for the Final Presentation

[City Bike Analysis](https://public.tableau.com/app/profile/tara.lightner/viz/CitiBikeClean/CitiBikeAnalysis)

## Summary
There are many other opportunites for data exploration athe would be benficial including visualization that would help answer the following:
- Further invesigation to see proportional how male and female differ
- The difference between weekday and weekend numbers by women vs. weekday and weekend numbers for men. This might work as a simple bar chart
- It might be worth looking at the proportional differences between customer and subscribers. This might be done with a bubble chart.
