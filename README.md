<span style="color:#0049DA">**Scope of the project**</span>: A Company that distributed proximity-based coupons has approached us and asked us to look into whether or not a driving customer will accept the variety of coupons. We were particularly asked to dig a bit deeper into bar coupons acceptance rate and were encouraged to analyze the acceptance rate of any other coupon category.

Please find here a <span style="color:#0049DA">**streamlined version of our observations**</span> with an in-depth analysis of the code base in the following file [Jupiter Notebook with detailed analysis and code base](https://github.com/iheavenAIML/AIML_liveproject_01/blob/main/practical_application_v01.ipynb):
1. In the presented to us dataset, the 'car' column mostly contained missing values (12,576 out of 12,684) and was unrelated to our task of analyzing driver behavior regarding coupon acceptance, so we decided to ignore it in our analysis.
2. Overall, 57% of driving scenarios result in immediate or later coupon usage across all coupon categories, while 43% result in coupon rejection.
3. Specifically for the 'bar' coupon, 59% of drivers decline it, and 41% accept it, indicating that a significant portion of drivers may still choose to drink despite the coupon offer.
4. Drivers visiting a bar 3 or fewer times a month show a lower acceptance rate of 53% compared to those visiting 4 or more times 77%.
5. Drivers over the age of 25 visiting bars more than once a month tend to accept the bar coupon at a rate of 70%.
6. Among drivers with frequent bar visits and non-kid passengers in occupations other than farming, fishing, or forestry, the acceptance rate is 71%.
7. Interestingly, drivers meeting the conditions mentioned in observation 6 still have a 71% acceptance rate, indicating that their occupation or marital status does not significantly affect coupon acceptance.
In summary, while most drivers decline bar coupons, some do accept them, especially those with more frequent bar visits. Additionally, the occupation and marital status of drivers appear to have little impact on bar coupon acceptance.

<span style="color:#0049DA">**Additional observations**</span>:<br>
•	For the 'Restaurant(20-50)' coupon, 56% of drivers decline it, while 44% accept it.<br>
•	Drivers in their mid-20s are the most likely to accept the 'Restaurant(20-50)' coupon, with an inverted correlation between age and coupon acceptance.<br>
•	The 'Restaurant(20-50)' coupon acceptance rate is similar for female drivers (43%) and male drivers (46%), suggesting that both genders tend to decline 'Restaurant(20-50)' coupons at a similar rate.

<span style="color:#0049DA">**Our recommendations**</span> to the company related to scoped analysis were as follows:<br>
•	Continue distribution of proximity-based coupons to driving customers.<br>
•	Discontinue distribution of coupons in 'Restaurant(20-50)' category.
