## Hotel Booking Cancellations Analysis

#### **Project Overview:**
This project analyzes hotel booking data, focusing on cancellations, guest types, room preferences, and seasonal booking patterns. The dataset is obtained from Kaggle (https://www.kaggle.com/datasets/mojtaba142/hotel-booking). The data was collected from 2015 to 2017, covering both city hotels and resort hotels. The goal is to understand booking behaviors, identify trends, and propose recommendations to improve booking processes and reduce cancellations.

#### **Dataset:**
- **Total Bookings**: 119,390
- **Total Cancellations**: 44,224
- **Booking Types**: City Hotel (79,330 bookings), Resort Hotel (40,060 bookings)
- **Countries Represented**: The dataset covers a global range of countries.

#### **Key Insights:**

1. **Cancellation Rates**:
   - **Overall Cancellation Rate**: Approximately 37%.
   - **City Hotel vs. Resort Hotel**: City Hotels have fewer total bookings but a slightly higher cancellation rate.
     - City Hotel cancellations: 33,102(75% of total cancellation)
     - Resort Hotel cancellations: 11,122(25% of total cancellation)

2. **Guest Types**:
   - Couples form the majority of bookings (81,560 total bookings), but also account for a significant number of cancellations (32,424).
   - Families and groups of friends exhibit lower booking and cancellation rates.
   - Single travelers tend to book fewer rooms, but they have a cancellation rate of almost 30%.

3. **Room Preferences**:
   - Desired rooms have a higher booking rate (104,473) but also face significant cancellations (43,422).
   - Rooms classified as "Un-Desired" face considerably fewer bookings (14,917), but very low cancellations (802).

4. **Monthly Booking Trends**:
   - **Peak months**: August (13,877 total bookings), July (12,661), and May (11,791).
   - **Low months**: January, November and December exhibit the lowest booking and cancellation rates.
   - Cancellations remain consistently high in popular months, especially during the summer travel season.

#### **Recommendations**:

1. **Targeted Retention for Couples**:
   Since couples form the largest group of both bookings and cancellations, creating tailored retention strategies—such as flexible cancellation policies or exclusive offers—could help reduce the cancellation rate in this segment.

2. **Room Allocation Efficiency**:
   - Cancellations for "Desired" rooms are quite high. Hotels should review room assignment strategies to ensure that booking preferences are honored or incentives are offered to those choosing "Un-Desired" rooms.
   
3. **Seasonal Promotions**:
   - During high-booking months (July-August), offering early booking discounts with stricter cancellation terms may help manage cancellation rates.
   - Low-demand periods (January, November and December) can benefit from promotional offers and last-minute deals to boost occupancy.

#### **Visual Summary (Dashboard)**:
![image](https://github.com/user-attachments/assets/4d9f16ba-7751-458d-931d-15a5d3bbed8c)

The dashboard provides visual insights into hotel bookings and cancellations, including:
- **Bookings by guest type**: Couples have the most cancellations, followed by family and single travelers.
- **Cancellations by room type**: Most cancellations are for desired rooms.
- **Booking trends by month**: Bookings peak during summer months, while cancellations remain high throughout.

This analysis helps the hotels optimize their booking strategies and reduce cancellations by better understanding guest behavior, room preferences, and seasonal trends.

---

This summary provides a clear overview of the dataset, key insights, and actionable recommendations to improve booking and cancellation management for hotels.
