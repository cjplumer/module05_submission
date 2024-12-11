# module05_submission
This GitHub repository is for the professional certificate in machine learning and artifical intelligence module 05 assignment submission.

The business problem for this assignment was to assess the likelihood of a survey respondant to accept a coupon offer to them under various different driving conditions and with different types of coupons.

I found the data collected by Amazon Mechanical Turk from the UC Irvine Machine Learning Repository in the URL below:
https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation

After exploring this data I conducted several types of statistical analysis to determine which variables in the survey results more likely contributed to those who accepted coupons vs those who did not.

There were 4 factors I focused on that I believe had the strongest correlation with coupon acceptance:
1) The type of coupon that was offered

Finding: Coupons for coffee houses, carry out & take away food, and restaurants with an average expense per person of less than $20 every month had higher acceptance rates than coupons for bars and restaurants with an average expense per person of $20 - $50 every month.

2) Driving destination

Finding: People driving home and to work were slightly more likely to not accept coupons vs those driving elsewhere

3) Passengers in the car

Finding: people driving with friends were more likely to accept coupons than those with their partner, kids or alone in the car

4) Coupon expiration date

Finding: Coupons with an expiration date of 1 day were much more likely to be accepted than those that expired in 2 hours


The Jupyter workbook that was used to come to the above findings is available in this GitHub repository here: module_5_assignment_workbook.ipynb
