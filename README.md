# Executive Summary - Traveltide Loyalty Program
## Introduction

In our current project,Travel Tide a prominent travel platform with over 1.6 million users and more than 5 million app sessions, seeks to improve user engagement by introducing a personalized rewards program. The goal of this project was to segment users based on their travel behavior and assign tailored perks that would encourage greater usage and loyalty.
The five perks proposed by marketing department are: Free hotel meal,Free checked in bag, No cancellation fees , Exclusive Discounts, 1 night free hotel with flight. First, we need to verify whether we have data to justify that clients would indeed be truly interested in such perks and then allocate each customer to the right one.
This executive summary outlines the approach taken, user segmentation strategies, key findings, and recommendations to launch a rewards program that targets active users effectively.

## Methodology

To identify users eligible for the rewards program, we considered those who had been active since January 4, 2023. After filtering users with more than 7 sessions during this period, we determined that 5,998 users were eligible. Older data were excluded to focus on recent travel behaviors.We used advanced SQL queries, Google sheet to clean our Data and group our customers into 7 different segments each aligned with proposed perks and Tableau to do further analysis. In our analysis we considered various customer interactions, such as booking behaviors, booked hotel info, booked flight info, spending behaviour etc. Indexes were derived from atleast 2 metrics. Additional groups emerged during the analysis that could not be easily categorized, leading to the addition of an uncategorized groups.


## Customer Segmentation Strategy

To ensure that perks were aligned with user preferences, we segmented users into seven distinct groups based on travel behavior metrics like:
Total trips, Average hotel stays, Flight booking behavior, Spending patterns.


The 7 segments are:
Family Vacationers, High-Spending Travelers, Budget-Conscious Travelers, Frequent Travelers, Spontaneous Travelers, Moderate Travelers, Occasional Travelers.

##Group Descriptions and Perk Allocation

Each segment was assigned a tailored perk based on their behavior and preferences:

## Summary

#### Finding 1: Moderate Travelers
Who are they? Users who take more than 3 trips or have low cancellation rates. Why this perk? They prefer convenient travel but don’t necessarily need luxury perks. Perk: "Priority boarding" – ensures a smoother travel experience. Total Users: 1,193
#### Finding 2: Budget-Conscious Travelers
Who are they? Travelers who frequently use discounted flights or hotels (over 30% of their bookings are discounted). Why this perk? They look for deals and appreciate savings. Perk: "Exclusive discounts" – gives them ongoing cost-saving opportunities. Total Users: 992
#### Finding 3: Family Vacationers
Who are they? Customers who book multiple rooms and longer stays (more than 3 days), usually traveling with family. Why this perk? These users appreciate savings and convenience when traveling as a group. Perk: "Free checked bag" – helpful for families with extra luggage. Total Users: 988
#### Finding 4: Frequent Travelers
Who are they? Users who take 4 or more trips and have a low cancellation rate (less than 10%). Why this perk? They value consistency and reliability in their travels. Perk: "1 night free hotel with flight" – rewards frequent bookings. Total Users: 918
#### Finding 5: High-Spending Travelers
Who are they? Customers who spend more than 1,500 Dollars on flights or 1,000 Dollars on hotels. Why this perk? These users enjoy premium services and high-end experiences. Perk: "Free hotel meal" – adds to their luxury experience. Total Users: 830
#### Finding 6: Spontaneous Travelers
Who are they? Users who book flights with less than 7 days' notice and have a low cancellation rate (under 10%). Why this perk? They appreciate flexibility and freedom from restrictions. Perk: "No cancellation fees" – reduces barriers to last-minute bookings. Total Users: 653
#### Finding 7: Occasional Travelers
Who are they? Users who don’t fit into the other categories, typically traveling less frequently. Why this perk? Even occasional users should feel appreciated. Perk: "Loyalty points" – encourages future bookings. Total Users: 424

## Insights and Key Findings

#### Popular Segments
Moderate Travelers (1,193 users) and Budget Travelers (992 users) make up the largest user segments. These groups respond well to perks related to convenience and discounts, making them ideal targets for cost-saving or efficiency-based rewards.
#### High-Spending Travelers
High-Spending Travelers (830 users) represent a smaller but valuable segment, with higher spending on both flights and hotels. These users prioritize premium services, suggesting an opportunity for more luxury-focused perks.
#### Spontaneous Travelers
Spontaneous Travelers (653 users) value flexibility, indicating perks like "No cancellation fees" could be crucial in promoting frequent, last-minute bookings.

## Recommendations

Based on these findings, we recommend the following steps:
  1. Tailor Marketing Based on User Segments Frequent Travelers should be targeted with loyalty benefits like free hotel nights to maintain their consistent usage.           Budget Travelers will likely respond best to cost-saving incentives and exclusive discounts.
  2. Enhance Family Offers For Family Vacationers, Travel Tide could further enhance the perks by offering family-friendly services such as group booking discounts or        activities suited to children.
  3. Focus on Retention for Occasional Travelers To boost engagement from Occasional Travelers, we recommend offering additional incentives like referral bonuses or          targeted promotions beyond just loyalty points.

  4. Premium Experiences for High-Spending Travelers High-Spending Travelers are more likely to become brand advocates if offered exclusive, premium perks like VIP           lounge access, upgraded hotel stays, or concierge services.
  5. A/B Testing for Perk Effectiveness: Conduct A/B testing within each segment to measure the effectiveness of different perks.
     
## Closing Remarks

In Conclusion: Our segmentation model ensures that every user feels recognized and rewarded, which will drive continued engagement. Through our detailed segmentation strategy, Travel Tide can implement a highly personalized rewards program that resonates with its users. By leveraging the different behaviors and preferences of each group, the company is well-positioned to drive user engagement and loyalty.








