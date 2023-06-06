# Investigate Hotel Business using Data Visualization

## Introduction
In this project we need to investigate and analyze the monthly hotel booking based on hotel type, impact of stay duration and lead time on cancellation rates. To investigate and analyze it I used Jupyter Notebook with python language.

## Data Preprocessing
- Handle Missing Values
- Handle Undefined Values
- Drop Useless Values

## Monthly Hotel Booking Analysis Based on Hotel Type
- Make Aggregate Data of Hotel Booking based on Hotel Type
- Normalize the Data because of Year Difference

![alt text](/img/hotel_guest.png)

This analysis focuses on examining the booking trends for each type of hotel. Both types of hotels receive the highest number of bookings around the months of June and July. Upon further examination, these months coincide with the Eid holiday and school vacations.

Additionally, in other months that do not coincide with any specific holiday, booking numbers appear significantly lower. As a result, the City Hotel experiences a significant decline in bookings in August and September.

## Impact Analysis of Stay Duration on Hotel Booking Cancellation Rate
- Make New Column of Total Stay Duration
- Make New Column of Cancellation Rate

![alt text](/img/night_spend.png)

This analysis focuses on examining the trend or correlation between the length of stay and the cancellation rate of hotel bookings. Both types of hotels show a positive trend, indicating that the longer the duration of stay, the higher the likelihood of the booking being canceled.

Moreover, it is observed that the City Hotel exhibits a steeper positive trend (significantly) compared to the Resort Hotel.

## Impact Analysis of Lead Time on Hotel Booking Cancellation Rate
- Make New Column of Lead Time Categories
- Make New Column of Cancellation Rate

![alt text](/img/lead_time.png)

This analysis focuses on examining the trend or correlation between the lead time (the time between booking a hotel and the arrival date) and the cancellation rate of hotel bookings.

The lowest cancellation rate is observed for bookings with a lead time of less than 30 days, and this applies to both types of hotels. The Resort Hotel maintains a relatively stable cancellation rate of 40%, whereas the City Hotel experiences a higher cancellation rate (60%) when the lead time is around 1 year.
