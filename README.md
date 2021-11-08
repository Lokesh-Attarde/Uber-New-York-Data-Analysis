
# Time Series Analysis - Uber New York Data Analysis Project 🔥🍁

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/Lokesh-Attarde/Uber-New-York-Data-Analysis)
  ![GitHub forks](https://img.shields.io/github/forks/Lokesh-Attarde/Uber-New-York-Data-Analysis)
  [![GitHub contributors](https://img.shields.io/github/contributors/Lokesh-Attarde/Uber-New-York-Data-Analysis.svg)](https://GitHub.com/Lokesh-Attarde/Uber-New-York-Data-Analysis/graphs/contributors/)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

![image](https://user-images.githubusercontent.com/84115928/140678953-1a9529d1-338f-4cd4-8084-7dca4075c02b.png)

# 📝Problem Statement
Analysis of the following is required by the Higher Management of Uber:

    1. Journey by Weekdays.
    2. Journey by Hour and with respect to each and every Months.
    3. Month with Max. Rides.
    4. Journey in terms of each Day.
    5. Analysis of Total Rides Month-wise.
    6. Rush w.r.t. Location and Hour-wise.
    7. Analyzing the popularity of Base by Months.
    8. Analyzing Rush w.r.t. Locations.
    9. Uber pick-ups by Months in New York City.
    10. Analysing Rush (Trips) in New York City.
    11. In-Depth Analysis of Rush in New York City in terms of Day & Hour-wise.
    12. Find-out which Base Number has Most Active Vehicles.
    13. Analysing which Base Number has Maximum Trips.
    14. Find-out Demand vs Supply of Uber Vehicles.

And many more!!

# ⏳ Dataset
Download the dataset for this project from following Link -
* [Uber New York Dataset](https://drive.google.com/drive/folders/180P1rEehdJ7aMTFLLoJ8XMoPgXY1OJ9j?usp=sharing)

# 📚 Data Analysis
This data contains on over 4.5 million Uber pickups in New York City provided with 8 different Files of raw data from April to September 2014. These files are separated by Month and each has the following Columns:

* **Date/Time** : The date and time of the Uber pickup.
* **Lat** : The latitude of the Uber pickup.
* **Lon** : The longitude of the Uber pickup.
* **Base** : The TLC base company code affiliated with the Uber pickup.
* **Pickup_date** : The date and time of the Uber pickup.
* **dispatching_base_number** : The TLC base company code of the base that dispatched the Uber.
* **active_vehicles** : Total active vehicles w.r.t. base number.
* **trips** : Total trips has been made.

# 🖥️ Technologies:
## 🛠️ Tools Used
* Jupyter Notebook is used as IDE.
* Pandas and NumPy are used for Data Manipulation & Pre-processing and Mathematical functions respectively.
* For visualization of the plots, Matplotlib, Seaborn, Plotly are used.
* Folium library were used to perform Spatial Analysis.
* GitHub is used as version control system

<p align="center">
  <img src="https://user-images.githubusercontent.com/84115928/140704607-501d334d-42a7-4271-9626-f4c95372eba4.png">
</p>

# 🎉 Tasks performed under Time Series Analysis:
* Extract the **"Derived Features"** from the **'Date/Time'** Feature.
* Performed ***Time Series Analysis*** on variety of ***Use Cases*** and Analysed as following:
  * Uber Rides by Weekdays.
  * Uber Rides by and with respect to each and every Months.
  * Month with Max. Rides.
  * Uber Rides in terms of each Day.
  * Total Rides Month-wise.
  * Rush w.r.t. Location and Hour-wise.
  * Popularity of Base by Months.
  * Uber pick-ups by Months in New York City.

# 🌱 Some Exciting Glimpse of the Visuals:
![Final Glimpse 1](https://user-images.githubusercontent.com/84115928/140725706-33748c98-c5b7-4e5c-80e3-b06b9cf1e7de.gif)
![Final Glimpse 2](https://user-images.githubusercontent.com/84115928/140718150-ae634d16-4d21-4250-814e-3a1b246c5996.gif)
![Final Glimpse 3](https://user-images.githubusercontent.com/84115928/140723990-69a9eebd-e130-4ba3-93ec-75ec5857b7f6.gif)
![Final Glimpse 4](https://user-images.githubusercontent.com/84115928/140724037-6c69ef19-e35d-45f9-89af-3f20b9852f54.gif)

For more details, please go through the Jupyter Notebook attached above.

# 💡 Conclusions
* "Rush" is definitely highest on "Thursday" followed by "Friday" and "Wednesday".
* Rush is definitely on Peak during Evening Time when people are logging off from their Work and At the same time, people go out for hang-out or to do a Shopping.
* "September" has the highest Rush or I would say, it has the Maximum Rides.
  Almost in the Couple of Last Days, in Each and Every "Month", we have "Maximum Rides".
* 'Thursday', is on the peak, whereas "Sunday" with respect to our Week-end, is on the root (bottom).
  And, In terms of the Rush, Hour & Location-wise - In the Early Morning at 8 o'Clock of almost each & every day, we've Maximum Number of Rush at this Location (I.e. 40.745) followed by Evening at 4 o'Clock.
* "Base" Number, which is exactly "B02617", gets Popular by Month.
* Almost in Each and Every Day, mostly in the "Evening Time", we have a "Rush" whereas on "Mid-Night", we don't have any kind of "Rush".
* Most of the 'Rush' is there on "Weekdays" rather than the "Week-ends".
  We have Majority of Rides are in "September", it might be because of Autumn Season, people go for excursions to enjoy the natural beauty.
* "Mid-Town Manhattan" is clearly a 'Huge Bright Spot', followed by basically "Upper Manhattan" and "Heights of Brooklyn".
* In this, "6th" Month, we have a Higher Number of Pick-up's followed by "May" and "April".
  We can also say that, The "Number of Uber Pick-up's" has been Gradually Increases throughout the 1st Half of 2015 in "New York".
* After the "Morning Rush", the Number of Uber Pick-up's doesn't decline much throughout the rest of the Morning and early "Afternoon" as well.
  And There is significantly More Demand of Uber Cabs in the "Evening".
* Base Number "B02764" is a Pioneer/Prominent. It has a Maximum Number of 'Active Vehicles' as well as it has a Maximum Number of 'Trips' as well.
* Base Number 'B02598' and 'B02682' are definitely Performed better in terms of Demands and Supply.
  Whereas Base 'B02512', it doesn't have that much Good Attention comparing to All other 'Base Number'.

And so many more!!

# 🎉 Help Me Improve
Hello Mr. Reader, if you find any bug or anything else that could add more value in this project then please consider raising it to me I will address them asap.
  
# 📫 Feedback
If you have any feedback, please reach out to me via [LinkedIn](https://www.linkedin.com/in/lokesh-attarde-145086141/)

