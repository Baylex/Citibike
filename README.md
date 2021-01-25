# Citibike
Mod 14: NYC Citibike with Tableau

## Overview of the statistical analysis:
Des Moines requested data for a business proposal.  August 2019 Citibike data from NYC was reviewed by looking at geographical data as well as data disaggregated by user types and genders to determine if it would be a good investment for Des Moines.  Other data points include usage durations, peak usage times, and the key target market. 

## Key Skills: 
1. Import data into Tableau.
2. Create and style worksheets, dashboards, and stories in Tableau.
3. Use Tableau worksheets to display data in a professional way.
4. Portray data accurately using Tableau dashboards.

## Link to Tableau Story: 
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Story1?publish=yes

## Cleaning the Data:
Jupyter Notebook was used to change the trip duration data to a datetime field.
![Pic](https://github.com/Baylex/Citibike/blob/main/Challenge/images/before_transformation.PNG)

![Pic0](https://github.com/Baylex/Citibike/blob/main/Challenge/images/after_transformation.PNG)



## Results of the NYC Citibikes Analysis:
### 1. Checkout Times for All Users
The Citibikes usage reaches a top of 3000 minutes per user.
![Pic1](https://github.com/Baylex/Citibike/blob/main/Challenge/images/0_User.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Users


### 2. Checkout Times by Gender
Males are significantly higher users than others. 
![Pic2](https://github.com/Baylex/Citibike/blob/main/Challenge/images/1_Gender.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Gender

### 3. Trips (Weekday per Hour)
6-10 am and 5-8 PM are peak riding hours during the weekday and 5 am to 10 pm on the weekends.
![Pic3](https://github.com/Baylex/Citibike/blob/main/Challenge/images/2_Trips.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Trips

### 4. Trips by Gender (Weekday per Hour)
Males are high users during the peak hours. 
![Pic4](https://github.com/Baylex/Citibike/blob/main/Challenge/images/3_TripGender.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/TripGender

### 5. Trips by Gender and User Type (Weekday per Hour)
Males subscribers are the highest users followed by female subscribers. 
![Pic5](https://github.com/Baylex/Citibike/blob/main/Challenge/images/4_UserType.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/UserType

### 6. Number of Rides per Hour
Non-peak hours are 1-5 am.  
![Pic6](https://github.com/Baylex/Citibike/blob/main/Challenge/images/5_Rides.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Rides

### 7. Number of Rides with Bike ID
The divergence line shows that there are high use on 1/3 of the bikes.
![Pic7](https://github.com/Baylex/Citibike/blob/main/Challenge/images/6_Repairs.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Repair

## Summary:

1. Bike Repairs for 1/3 of the Citibikes need to be done during non-peak hours around 1-5 am. 
2. Male subscribers are the highest users and follow the traditional high use times of travel to and from work.  
3. Target market should be males needing transportation to work and weekend activities and push for subscribing to the services. 

## Additional Analysis: 

### 1. Ride Starting Locations by Gender
Males are more likely to start a trip farther than the main city center of NYC than others. 
![Pic8](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra1.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/Start

### 2. Ride Ending Locations by Gender
Males are more likely end a trip across the river in the southwest are of NYC than others. 
![Pic9](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra2.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/End

### 3. User Type Starting Location
Subscribers are more likely to start trip farther than the main city center of NYC than others. 
![Pic10](https://github.com/Baylex/Citibike/blob/main/Challenge/images/extra3.PNG)
https://public.tableau.com/profile/julie.pyle2236#!/vizhome/Mod_14_Challenge/UserTypeMap
