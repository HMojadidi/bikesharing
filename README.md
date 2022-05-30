# Bikesharing

# Overview of the analysis:
To convince investors that a bike-sharing program in Des Moines is a solid business proposal, I am presenting a data analysis report of a bikesharing company in New York. I imported data into Tableau, created and styled worksheets, dashboards and stories. My observations were based on data from August 2019 Citibike data from NYC. I compiled my analysis observing trends in factors such as gender, usertypes, usage trends in days of the week, time and geographical data.

## Link to Tableau Story:

[Tableau Story](https://public.tableau.com/app/profile/hoda.mojadidi/viz/NYCBikesharingDataAnalysis/Story1)

# Data Cleaning:

First I was required to change the trip duration data to a datetime field. I did this using Jupyter Notebook.

<img width="564" alt="Screen Shot 2022-05-30 at 12 41 02 AM" src="https://user-images.githubusercontent.com/95712234/170918422-8ea5b3a6-ac34-49a1-a7cb-cb5cb92570ad.png">

<img width="629" alt="Screen Shot 2022-05-30 at 12 42 13 AM" src="https://user-images.githubusercontent.com/95712234/170918546-9684c6a8-70e8-43ab-a2cd-a346235072e9.png">

# Results:

## 1. Checkout Times for Users:

There is demand for bike usage for as little than an hour, peaking at 5 minutes.

![Screen Shot 2022-05-30 at 12 48 08 AM](https://user-images.githubusercontent.com/95712234/170919044-2ef98b21-2407-44ba-b318-ffced6d72ad9.png)

## 2. Checkout Times by Gender:

Males are the majority of these bike riders. Women trail by 1/3 in bike usage.

![Screen Shot 2022-05-30 at 12 55 57 AM](https://user-images.githubusercontent.com/95712234/170919751-7e93f6d3-e554-45b9-88b5-9bd501932122.png)

## 3. Trips by Weekday per Hour:

Peak bike usage hours are at their peak around 8 - 10 a.m. and 5 - 7 pm in the evenings.

![Screen Shot 2022-05-30 at 12 57 22 AM](https://user-images.githubusercontent.com/95712234/170919876-08ab676b-b6fd-45db-879f-76139383e8aa.png)

## 4. Trips by Gender (Weeday per Hour):

Men are the majority of bike riders and they use them most during morning and evening workday timings.

![Screen Shot 2022-05-30 at 12 59 24 AM](https://user-images.githubusercontent.com/95712234/170920057-d508c233-afa8-4ec1-924d-b84b94f5aa33.png)

## 5. Trips by Gender and Usertype (Weekday per Hour):

Men who are subscribers tend to bikeride the most. Women subscribers slightly use bikes more than their customer counterparts.

![Screen Shot 2022-05-30 at 1 01 18 AM](https://user-images.githubusercontent.com/95712234/170920198-852cacdc-acf7-499c-82fe-76846e13fb0a.png)

## 6. Number of Rides per Hour:

Peak usage is during  8 - 10 a.m. and 5 - 7 p.m. The lowest usage time is around 3 - 5 a.m.

![Screen Shot 2022-05-30 at 1 02 42 AM](https://user-images.githubusercontent.com/95712234/170920313-b1a2d6d2-d475-4a9f-80c2-57acf50ec1a9.png)

## 7. Customer breakdown:

The vast majority of bike users are subscribers.

![Screen Shot 2022-05-30 at 1 18 33 AM](https://user-images.githubusercontent.com/95712234/170921863-242258c4-f5d9-4333-bb08-ef2894b4b98b.png)

# Summary:

1. The best time for bike maintenance would be around 3 - 5 a.m. as these times have the least number of users.
2. Male subscribers are the vast majority of users and seem to use the bikes throughout week. There are no particular trends with male customers throughout the week. Females subscribers have a slight lead over customers. It would be best to encourage subscription to both male and female customers. 
3. The highest number of users tend to be around high-traffic tourist areas, such as downtown Manhattan in New York. It would be best to check bike inventory for Des Moines high traffic areas so that they may meet the added demand for bikes.
 
# Additional Analysis:

## 8. Top Starting Locations by Gender:

A trend worth noting is that female users start in similar geographical area distributions as their male counterparts.

![Screen Shot 2022-05-30 at 1 48 47 AM](https://user-images.githubusercontent.com/95712234/170925331-06c855c2-41ff-4a4b-85d7-24995fa09513.png)

## 9. Ride Ending Locations by Gender:

Female bikeriders tend to stay within the same traditional originating areas rather than venturing out. Those who would bike away from the downtown Manhattan areas were mostly men crossing the Hudson River. 

![Screen Shot 2022-05-30 at 1 52 29 AM](https://user-images.githubusercontent.com/95712234/170925787-689b84e1-50a5-47b3-9797-2dd798d5eb8a.png)


