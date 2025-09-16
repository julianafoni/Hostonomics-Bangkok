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
