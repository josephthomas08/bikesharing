

# Bikesharing project overview 

The bikesharing project and its possible positive impact on the enviornment with additional health benefits for either gender and people of all ages were studiend and analysed from existing New york bikesharing data.

The intent is to see the possiblity of replicating the same success in city of Des  moines with healthier alternative of travel and adding on the healtyh benfits for present and future generations. 

Considering the dynamics of such an investment in a city which could possibly be different than New york a better analysis will help the potetital investors to invest in profitable business and at the same time contributing into a excellent future for new generations by keeping greener, healthier  environment and well being.

The study will be more based out of the month of August when the usage is at peak and provide a deep study from mutiple facets to understand the business better.  The tool we are using for this project will be analysed and presented with TABLEAU. 




## Deliverable 1.0 

### D 1.1 Convert the data in the "tripduration" column  to a datetime datatype 

#### The datatypes of each column in the DataFrame was loaded in the Jupyter notebook and trip duration columm data typte as loaded below was targeted to converted as datetime.


<img width="1093" alt="D1 1a" src="https://user-images.githubusercontent.com/75267605/113317429-5c5da200-92dd-11eb-89e9-2163c87b9dd1.png">





#### Additional column named tripduration_datetime is created in datetime format as needed 


<img width="1099" alt="D1 1b" src="https://user-images.githubusercontent.com/75267605/113317465-61baec80-92dd-11eb-80b7-42e50439aef3.png">


#### The last comun as required was converted inot date time format
<img width="1087" alt="D1 1" src="https://user-images.githubusercontent.com/75267605/113317488-67183700-92dd-11eb-9207-6bba2e2cc9a0.png">

 
### D 1.2 The DataFrame is exported as a new file without the index column 


#### Code was written in jupyer notebook to crea an updated .csv file with tripdurantion_datetime included.



<img width="1149" alt="D1 2" src="https://user-images.githubusercontent.com/75267605/113319126-215c6e00-92df-11eb-8300-5233d27b72ed.png">



# Results 

The Tableau tool gives us a the option to present the new intivative in Des Moines to our potential investors in easier to understand the beneifts of community support intiative. I will like to enagage the audience for this project with a story which is going to assist this poitive intiative beyond the profitability of this project.

## Number of Rides 

<img width="1326" alt="Number of rides " src="https://user-images.githubusercontent.com/75267605/113325200-1953fc80-92e6-11eb-8a1a-9df6674c3a4b.png">


## Note -The total number of rides in this dataset for the month of August 2019 are 2,344,224. This dataset includes  the rides by genders (male, female, unknown) and type of customers (subscribers and daily customers.

The information gives us a estimate of what we can expect in any similar cities. This data also will ecnourage the city authorities to envision their team to look into ways to encourage the community to engage positively in reducing carbon footprint.

## Customer Breakdown

<img width="1329" alt="D3 2 Customer breakdown" src="https://user-images.githubusercontent.com/75267605/113325308-41436000-92e6-11eb-821c-e98cde73ab97.png">

The dataset and focussed dashboard gives us the overall two types of Users, daily customers (random users, Vacationers) and subscribers (regular users). The dat set shows that 81% are subscribers and rest 19% are daily customers.

The data Set will help city and state to envision their tourist operators of how they can monetize and promote bike riding during the visit into their city.

## Gender Breakdown

<img width="1325" alt="D3 3 Gender Breakdown " src="https://user-images.githubusercontent.com/75267605/113325289-3983bb80-92e6-11eb-98db-84ef4c270eea.png">

The data set shows three types of people marked out daily bikesharing activty.

#### 1. Male- 1,530,272 (65.28%)
#### 2. Female- 588,431 (25.10%)
#### 3. Unknown- 225,521 (9.62%)

From the data set it is quite clear than considerable number of male gender are comfortable in usage of bikes compared to female and unknown gender. 
These information for new city will assist us to know our target customers and at the same time gives the authorities additional reason to market the services to female gender and provide more options in the bikesharing app.



## Deliverable 2.0 

### D 2.1 There is a line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour.

## Check out time for Users

<img width="1329" alt="D2 1 Checkout Times for Users" src="https://user-images.githubusercontent.com/75267605/113319928-f7577b80-92df-11eb-8b80-6133d811220f.png">


The intent of this visualization is show the time these bikes are checked out for all the users. The image tells us that most of the bikes are checked out for a duration of 20 mins and none of the rides have exceeded 50 minutes of usage.


### D 2.2 There is a line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender.


## Check out time for Gender 

<img width="1330" alt="D2 2 Checkout Time for Gender " src="https://user-images.githubusercontent.com/75267605/113319965-fd4d5c80-92df-11eb-8151-b8433a84b3b8.png">


The intent of this Viz is to show the length of time the bikes were cjhecked out by each gender. The time os usage was similar for all genders which was 20 min and 50 mins (max).




### D 2.3 A heatmap is created showing the number of bike trips for each hour of each day of the week.


##  Trips by weekday per hour

<img width="1326" alt="D2 3 Trips by Weekday per Hour " src="https://user-images.githubusercontent.com/75267605/113320005-0807f180-92e0-11eb-98ed-3ac83a26491c.png">

The above detailed heatmap visualtiaon was provided to highlight the peak  hours of the day and busiest days of the week. The heat map shows that from 7-9 am and 5-7 pm of teh weekdays are the peak hours while saturdays are busiest from 10AM-7PM.

Additionally it is noted that on sundays the peak is between 11AM-5PM.

This gives us a insight that in new cities saturdays and sundays higher usage could be as a result of heavy tourist influx. A more deatiled survey and dat influx from the tourism industry will help us to propose the possibility of influencing the team to increase the usage of bikes during non-peak hours.




### D 2.4 A heatmap is created showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender.


## Trips by Gender weekday per hour

<img width="1327" alt="D2 4 Trips by Gender weekday per hour " src="https://user-images.githubusercontent.com/75267605/113320020-0d653c00-92e0-11eb-8034-490007eb240d.png">

This Viz was initiated to re-emphasize on our earlier study and additionaly provides a detailed breakdown on usage by different gender. The peak hours on weekdays and weekends are similar to what we detailed earlier.


### D 2.5 A heatmap is created showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender.

## User Trips by Gender by Weekday 

<img width="1332" alt="D2 5 User Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/75267605/113320056-16eea400-92e0-11eb-918b-05d8d0690625.png">

The image above provides us information on the two types of users especially daily customers and subscribers their usage pattern over the weekdays. The gender breakdown of the the types of users are provided and we learn that bot customers and susbcribers is same throught out the week.


## Number of trips by Gender and age 


<img width="1330" alt="Number of Trips by Gender   Age" src="https://user-images.githubusercontent.com/75267605/113331284-c2522580-92ed-11eb-82a8-e6d2a5348b55.png">

This graph speaks very specific to trips made by the three genders and two types of customers in relation to their age and gender. We notice that users born in 1990 are major users of bikes.
We do notice certian spikes of users born in the year of 1969 but gender of such users were not very clear. Further research, surveys and investigations will assist us to propose to the investors of how we can implement similar healthy business initiatives by including all the stakeholders of their role to participate.



## Bike Utilization 

<img width="1320" alt="D3 4 Bike Utilization " src="https://user-images.githubusercontent.com/75267605/113325364-528c6c80-92e6-11eb-9faf-5051b306dc4b.png">


The bike utization graphs gives us windows of oppotunites to tactfully enageg in bike maintatinance during least usage time lines. The opertaional cost will have major impact with right approach to maintenance by keeping the downttime of bikes to bare minimal. Preventive and corrective maintainance will depend on knowng the time span when the usage is less.

We are assited well with Tableau in knowing the relevant Bikeid and zie of bubble to identify the usage and time our maintaince activty.

# SUMMARY

In Conclusion we will like to provide a brief summary from the great visuals Tableau offered from the data set we have from NYC bikesharing data.

The bikes as we see were manily used by males during the weekdays to commute to their work place and bikes assisted them to avoid peak hours. The peak hours usage further confirms this assumption.
The benefit of such usage will be duplicated for cities similar to New york. For a city like Des Moines where the population is less compared to NYC should be better studied and researched.
It was further noted taht the rides on an average were restricted to 20 minutes.
The number of trips by Gender, age and user types tells us who will be our potential clients for the business. This further gives us insight on how city, county and tourism authorities could positively engage in developing this Business intiative.

The relative comparision of population in Des moines and more data from the city and Tourism authorities in Des moines and NYC will give us more insight into the possible breakdown of number of bikes we will need to estimate the CAPEX and OPEX cost.

Further details on the existing Public transport, key tourism locations will assist us to provide the 20 min start to stop bike rides comfort of the users.

Overall we believe that this initiative of Bikeshare being implemented with right Capex and Opex will be great for cities and states to engage in and provide a healthy environment for generations to come.





