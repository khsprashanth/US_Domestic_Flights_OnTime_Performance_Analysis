# US Domestic Flights On-Time Performance
## by Prasanth Kadimisetty


## Dataset

> The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website. BTS started gathering details about the causes of flight delays in June 2003. Sypnosis of Data and raw data are made available to the public at the time the Air Travel Consumer Report is released.
 
> I have downloaded the dataset which consists of all the domestic flight records in the  year 2012 from https://packages.revolutionanalytics.com/datasets/AirOnTimeCSV2012/ 


> This data consists the all flight records in the year 2012. It has 6096762 rows and 34 columns. 13908 data points were removed due to inconsistencies and missing information.Attributes included arrival delay, departure delay , cancellation code, carrier name etc.

> I extracted The origin and destination airport names from the lookup datasets I have downloaded from <br>
 http://stat-computing.org/dataexpo/2009/supplemental-data.html.

## Summary of Findings

> I tried to find the top5 airports ranked by no. of flights records **"William B Hartsfield-Atlanta Intl"** has most flight records approx 400000 stand in 1st position and **"Los Angeles International"** stand in 5th pos with arounf 200000 flight records.

> I found that the no. of flight records are more in the month **July**. We can also observe there is **sharp decrease** in flights from the month **August to September** and there is **sharp increase** in the no. of flights records from the month **February  to March.**

> There is one flight which is arrived **1823 min(30 hrs)** late compared to actual arrival time which is the most delayed flight in our dataset.There is one more flight which arrived **411 min(6 hrs)** early than the actual arrival time



> **69%** flights speed up during the mid flight. **26.76%** flights get more delayed using the mid flight. **3.35%** flights neither increase nor decrease the delay using the mid flight.

> **Atlantic Southeast Airlines** have **highest** no. of cancelled flights**(15257)** and **Hawaiin Airlines** have **least** cancelled Flights**(67)**. **The American Airlines Inc** and **Southwest Airlines Co.**  have the almost same no. of cancelled flights. 

> I found that highest no. of flights are cancelled on Tuesday and I also found that Saturday has Less no. of flights therefore have less delays compared to other days of the week.

## Key Insights for Presentation


For the presentation, I just focused on the Behaviour of flights mid air and leaved out the distributions of arrival delay and departure delay and I Categorised my analysis across year into two categories i.e, Analysis across months and analysis across days of the week.
   
And then finally I focused on ontime performance of carriers. 

I found many insights which I included in analysis ,some of them are:

> while calculating how many flights speed up and reach early than the actual arrival time I found that approx 78% of flights do that!.Thats really intresting!! that most of the flights not only cover their departure delay but also reach early than the actual arrival time.

> The top 5 Airlines ranked by no. of fights operating (SouthWest Airlines,Atlantic Southeast Airlines,Delta Air Lines , Skywest Airlines and United Airlines) have mean carrier delay of around 20 min perflight. SkyWest Airlines done an amazing job with 13.4 min mean carrier delay per flight. Virgin Airlines being in the last position have least mean carrier delay of 10 min per flight. On the other hand, taking responsibility of a higher number of flights results in a higher chance of having an extreme waiting situation.

> The Average Arrival delay is Less or equal to Average Departure delay of any carrier.The Average **Arrival Delay** is least for **Alaska Airlines Inc.** and highest for  **Frontier Airlines Inc.** The Average **Departure Delay** is least for **Hawaiian Airlines Inc.** and highest for **United Airlines Inc.**