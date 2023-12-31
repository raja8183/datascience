This project, Practical Application 1, is for a data science assignment based on the data from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50). 

The project notebook can be found [here](./prompt.jpynb)

Below are a few observations from the data analysis for Customers who visit Bar : 

1. Drivers choose to mostly accept coupons for 'Coffee House', 'Restaurant less than 20 mins away' or 'Carry out & Take Away'
2. Majority prefer to accept Bar/Cofee House coupons when the temperatures are higher than 50
3. Drivers prefer to accept Restaurants coupons when the temperature is around 80 and the restaurants are less than 20 mins away.
4. Drivers prefer to stay home and accept Carry out & Take away when the temperatures are around 30, colder temperatures not willing to drive.
5. Acceptance rate of customers who went to a bar 3 or fewer times a month is 12.16% compared to customers who went to a bar more than 3 times is 6.99%
6. Only 20.9% of Drivers visit bar more than once and are older than 25
7. acceptance rate between drivers who go to bars more than once a month, had passengers that were not a kid and had occupations other than farming, fishing, or forestry is 71.3% compared to all Drivers who have accepted Bar coupons.

