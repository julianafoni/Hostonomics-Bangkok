# Hostonomics-Bangkok
An analytical project exploring Airbnb listings in Bangkok. This project applies descriptive and inferential statistics to identify key market insights, visualize host and pricing dynamics, and deliver actionable recommendations for stakeholders.

![Hostonomics Bangkok Cover](Hostonomic-bangkok.png)

## Context
Bangkok is one of the most popular tourist destinations in Southeast Asia, attracting millions of visitors each year. This growth in tourism drives the rising demand for alternative accommodations, one of which is provided through the Airbnb platform. The Airbnb market in Bangkok is highly dynamic:
 - **Geographical variation** → Each neighborhood has its own characteristics. Some premium areas are dominated by entire homes/apartments, while backpacker zones offer a higher share of shared/private rooms.
 - **Price variability** → Daily rental prices are significantly influenced by location, room type, number of reviews, and minimum stay policies.
 - **Competition among hosts** → The market is dominated by a mix of individual hosts (single-listing) and professional hosts (multi-listing). This creates unique competitive dynamics, where fairness and business strategy become critical issues.
 - **Fluctuating demand** → Listing popularity can be measured by the number of recent reviews (number_of_reviews_ltm) and availability (availability_365). Listings with many reviews but low availability reflect properties with high demand.

In this context, analyzing Airbnb data in Bangkok is not only crucial for understanding the market but also for:
-	Helping hosts set pricing strategies and increase engagement.
-	Helping the platform (Airbnb) develop automated pricing recommendation features and maintain market balance.
-	Helping investors identify neighborhoods and property types with strong potential for long-term investment.

## Problem Statement
The Airbnb market in Bangkok faces major challenges: highly variable rental prices, uneven demand patterns across neighborhoods, and the dominance of professional hosts that may reduce the competitiveness of individual hosts. Stakeholders (hosts, the platform, and investors) often lack structured information to make data-driven decisions.

### Goal
-	Identify the key factors influencing daily rental prices (price determinants).
-	Map demand patterns through geographical distribution, listing popularity, and customer engagement.
-	Analyze host behavior (supply side) to understand the differences between individual hosts and multi-listing hosts.
-	Deliver actionable data-driven insights for hosts, the platform, and investors.

### Analytical Approach
To achieve these goals, the analysis combines multiple methods:
- Statistical Analysis → Descriptive (mean, median, distribution) & Inferential (ANOVA, t-test, chi-square) to test differences across groups.
- Geospatial Analysis → Scatter plot maps, heatmaps, and crosstabs (neighborhood × room type) to understand geographical distribution.
- Correlation & Regression → Correlation matrix, linear regression, and random forest regression to measure the impact of variables on price and engagement.
- Cluster & Segmentation → Cluster analysis to group listings based on engagement, and host segmentation (single vs. multi-listing).

## Insight & Key Recommendations
![Alt Text](Insight%20Bangkok%20Airbnb.png)
### Insight 1: 
#### Geographical Distribution & Room Type
The analysis reveals significant differences in the distribution of Airbnb listings in Bangkok.
- Some premium neighborhoods are dominated by entire homes/apartments with higher prices.
- Backpacker areas tend to offer private/shared rooms with lower prices.
- Correlation with popularity (number of reviews) shows that premium neighborhoods also attract higher engagement.

Recommendation:
- Hosts in non-premium areas can enhance attractiveness through service differentiation or added facilities.
- Platform (Airbnb) can use geographical segmentation for targeted promotional strategies.
- Investors are advised to focus on premium neighborhoods with consistently high engagement.

### Insight 2:
#### Price Determinants
- Results from ANOVA/Kruskal-Wallis show that location and room type are the most significant factors influencing rental prices.
- Correlation analysis indicates that the number of reviews has an effect, but weaker compared to location.
- Regression and random forest analysis confirm the feature importance ranking: Location > Room Type > Reviews > Minimum Nights.
  
Recommendation:
- Hosts can implement dynamic pricing strategies based on significant variables rather than intuition alone.
- Platform (Airbnb) can develop automated pricing recommendation features to enhance fairness.

### Insight 3:
#### Engagement & Popularity
- Listings with many reviews in the last 12 months but low availability fall into the high-demand property category.
- Minimum stay policies significantly affect popularity: the more flexible, the higher the likelihood of engagement.

Recommendation:
- New hosts may consider adopting more flexible minimum stay policies to attract more guests.
- Investors can identify high-demand properties as medium-term investment opportunities.

### Insight 4:
#### Host Behavior (Single vs Multi-listing)
- Multi-listing hosts (professional) dominate the majority of listings, set higher prices, and attract more reviews.
- Single-listing hosts tend to struggle to compete, especially in premium neighborhoods.

Recommendation:
- Platform (Airbnb) may consider regulations or incentives to ensure fairness between individual and professional hosts.
- Investors can replicate the pricing strategies of professional hosts.
- Individual hosts should focus on niche markets or unique services to improve competitiveness.   

## Assets


