# Background
Business performance analysis is an important key for companies to achieve success in their business. Companies can conduct analysis to identify their problems, weaknesses, and strengths. In the hospitality business, it is important to understand customer behavior. By understanding customer behavior, companies can find out what factors influence customers in making hotel reservations. In addition, the company can also identify what products or services are not selling well in the market. This is done to adjust the appropriate business strategy so that the company can improve customer experience and can achieve long-term business goals.

# Objective
Create data-driven visualizations as insights for the hotel business.

# Business Questions
* What types of hotels are most frequently visited by customers?
* Does the duration of stay affect the hotel booking cancellation rate?
* Does the time gap between hotel booking and guest arrival day affect the hotel booking cancellation rate?
  
# Data
The data used is data from hotel companies from 2017 - 2019.

# Data Pre-Processing
* There are 4 features that have null values, the handling of the missing values is followed up by filling it with the value "unknown".
* There is a value that does not match the categorical feature "meal", the value is followed up by performing the **.replace()** method with the appropriate value.

# Analysis
## **1. Analysis of the Number of Hotel Bookings per Month by Hotel Type***
<br>
<img src="images/Image 1.png" alt="Logo" width="1000" height="auto">
Based on the plot image, the increase in the number of hotel reservations has increased in two periods, namely May - July then October - December. The increase occurred because the time period has entered the holiday season, for the first holiday season from May - July is the summer holidays, while the second holiday season is Christmas and New Year.

## **2. Analysis of the Effect of Duration of Stay on Hotel Booking Cancellation Rate**
<br>
<img src="images/Image 2.png" alt="Logo" width="1000" height="auto">
The booking cancellation rate for the City Hotel category increases along with the length of stay. Meanwhile, for the Resort Hotel category, the booking cancellation rate has a high percentage for the duration of stay for 2-3 weeks and 3-4 weeks.

## **3. Analysis of the Effect of Lead Time on Hotel Booking Cancellation Rate**
<br>
<img src="images/Image 3.png" alt="Logo" width="1000" height="auto">
The booking cancellation rate for the City Hotel category generally increases along with the duration of the lead time. As for the Resort Hotel category, the booking cancellation rate has a high percentage in the lead time duration of 9 months and 11 months, but when viewed as a whole the Resert Hotel graph can also be said to have an increasing percentage of cancellation rates.

# Conclusion
* What type of hotel is most frequently visited by customers?<br>
The "City Hotel" category is more booked by customers by 66.4% than "Resort Hotel". The increase in the number of City Hotel bookings has increased in two periods, namely May - July then October - December. The increase occurred because the time period has entered the holiday season.
<br>
<br>

* Does the duration of stay affect the cancellation rate of hotel bookings?
The correlation between the length of stay from the entire range of 1 week to more than 4 weeks has an influence on the booking cancellation rate for the City Hotel category. However, the Resort Hotel category has the highest percentage of cancellations in the duration of stay of 2-4 weeks.
<br>
<br>

* Does the time gap between hotel booking and guest arrival day (lead time) affect the hotel booking cancellation rate?
The correlation between the length of the lead time duration has an influence on the booking cancellation rate, more specifically for the City Hotel category. As for the Resort Hotel category, the booking cancellation rate has a high percentage in the lead time duration of 9 months and 11 months, but when viewed as a whole the Resert Hotel graph can also be said to have an increasing percentage of cancellation rates.
<br>

# Recommendations
* Provide promotions for City Hotel because it is more frequently booked by customers, and promotions can be focused on the holiday season where the number of bookings is high such as May-July and October-December.
* The hotel can consider strategies to reduce the level of lead time because it affects the cancellation rate of hotel reservations, such as providing promotions or incentives for customers who book in advance.
