# Customer-Airlines-Booking-Dashboard
This dashboard offers a comprehensive visual analysis of customer booking data for an airline, built using Power BI. The primary goal is to transform complex booking information into actionable insights through dynamic visualizations.

Segmentation Information
Purchase Lead Distribution:
1-7 days "Last Minute", 8-30 "Short-Term", 31-90 "Standard Planner", 91-180 "Advance Planner", 181+ "Super Planner"

Length of Stay Distribution:
1-7 days "Short Trip", 8-21 "Standard Trip", 22-60 "Extended Trip", 61+ "Long Trip"

source file: https://www.kaggle.com/datasets/anandshaw2001/airlines-booking-csv

Insight and Conclusion Breakdown

Overall Key Metrics and Conversion Challenge
The total booking volume is 49,900, resulting in only 7,463 completed bookings. The resulting booking completed rate is a notably low 14.96%, especially when compared to a healthy industry standard, which is often in the 50–80% range.
The average purchase lead is 84.95 days, which indicates that customers are generally booking well in advance. This long lead time could be a key reason for the low completion rate , as a significant number of people may be "soft-committing" and are more likely to drop off if their plans change or they find a better price closer to the date. The average number of passengers per booking is 1.59, confirming that bookings are typically for one or two people.
Analysis by Trip Planning and Duration
Purchase Lead Distribution Insights
Bookings are concentrated in the mid-range planning categories. The majority of total bookings occur with Standard Planner (17,000), Short-Term (12,300), and Super Planner (7,200).
Crucially, bookings closer to the travel date are more likely to be completed. The Last-Minute (1–7 days) category has the highest completion rate at 16.67%, followed closely by the Short-Term (8–30 days) category at 16.26%. This suggests that the intent to purchase is strongest for immediate needs. Conversely, long-term bookings have a higher drop-off rate , with the Super Planner (180+ days) and Advance Planner (91–180 days) categories having the lowest completion rates at 13.89% and 13.95%, respectively.
Length of Stay Distribution Insights
Short trips (1–7 days) are the most popular, accounting for the largest number of total bookings at 25,000, which is a clear indicator of market preference for shorter getaways.
The Long Trip category (61+ days), despite having the fewest total bookings (4,000), has the highest completion rate at 25%. This is a significant finding that suggests customers who commit to an extended trip are highly motivated and less likely to cancel.
In contrast, the Extended Trip category (22–60 days) has a notably low conversion rate of just 7.14%, despite having 14,000 total bookings. This high drop-off rate for this specific trip duration is a point of concern that may require further investigation.
Sales Channel and Daily Volume Analysis
Sales Channel Performance
The Internet channel is the dominant source, accounting for 44,300 total bookings with a completion rate of 15.47%. The Mobile channel has 5,608 total bookings and a significantly lower completion rate of 10.86%. While the Internet channel generates a much higher volume of total bookings, the Mobile channel's low conversion suggests that the mobile experience may be less user-friendly or have technical friction points, making optimization beneficial for increasing completed bookings.
Booking Volume by Day
Booking volume peaks at the start of the week and gradually decreases towards the weekend. Monday is the highest booking day with 8,100 bookings, while Sunday has the lowest volume at 5,800. This trend indicates that booking activity is a work-week-dominated behavior, likely influenced by business or vacation planning at the start of the week.
Ancillary Services Performance
The data clearly shows a hierarchy of popularity among ancillary services. Both Seat Selection (70.3%) and Extra Baggage (66.9%) have very high purchase rates, suggesting they are considered essential or highly valuable by a large percentage of customers. Conversely, In-Flight Meals are a less common purchase at 42.7%, indicating they are seen as more of a "nice-to-have" or are of lower perceived value.
Overall 
The overall conclusion highlights a significant challenge in converting initial interest into completed sales, but also points to clear opportunities for targeted improvement.
The most critical finding is the low Booking Completed Rate of 14.96%, which is considered very low against industry benchmarks. This high drop-off rate is largely driven by the long average purchase lead time of 84.95 days, as customers booking far in advance are more likely to "soft-commit" and abandon the transaction later.

