# AtliQ Grands Business and Data Intelligence Project

## Overview
AtliQ Grands owns multiple five-star hotels across India and has been a key player in the hospitality industry for over 20 years. However, due to strategic moves from competitors and ineffective decision-making in management, AtliQ Grands has been losing its market share and revenue in the luxury/business hotels category. To regain market share and revenue, the managing director decided to incorporate "Business and Data Intelligence" into their decision-making processes. Since AtliQ Grands does not have an in-house data analytics team, they decided to hire a third-party service provider to analyze their historical data and provide actionable insights.

As a data analyst, I was tasked with creating a dashboard, defining key metrics, and uncovering insights from historical data to help improve operational efficiency and guide data-driven decisions.

## Objective
The primary objective of this project was to:
- Enable data-driven decisions for AtliQ Grands’ revenue management team.
- Enhance operational efficiency by analyzing key metrics like Average Daily Rate (ADR), Revenue per Available Room (RevPar), customer ratings, and occupancy rates.

## Dataset
The project was based on five CSV files containing relevant hotel and booking data spanning the months of May, June, and July. Below is a description of each dataset:

1. **dim_date**: Contains date information, including week numbers and day types (weekend or weekday).
2. **dim_hotels**: Contains metadata for each hotel, including unique ID, hotel name, category (Luxury/Business), and city.
3. **dim_rooms**: Contains room type and class information for each hotel.
4. **fact_aggregated_bookings**: Contains aggregated booking details, including successful bookings, room categories, and hotel capacity.
5. **fact_bookings**: Contains detailed booking information, such as booking ID, revenue, ratings, and booking status (e.g., cancelled, checked-out, or no-show).

## Key Findings
1. **Dynamic Pricing**: Some hotels are not implementing dynamic pricing, which is a major source of profit, as seen from ADR and RevPar.
   ![Image 1](https://github.com/d-sutariya/AtliQ-Grands-Business-and-Data-Intelligence-Project/blob/main/images/Screenshot%20(162).png)
   
3. **Customer Ratings and Occupancy**: Hotels with lower average customer ratings in certain cities have lower occupancy rates. Focusing on improving ratings could significantly boost occupancy, following the Pareto 80/20 rule.
   
5. **Website Pricing Strategy**: Hotels are selling rooms at the same price on their websites as on third-party platforms. Reducing prices on the hotel's own website could help avoid commission fees and increase direct bookings.

   ![image 2](https://github.com/d-sutariya/AtliQ-Grands-Business-and-Data-Intelligence-Project/blob/main/images/Screenshot%20(163).png)

## Recommendations
1. **Implement Dynamic Pricing**: Encourage the adoption of dynamic pricing to adjust room rates based on demand, competition, and other factors to optimize revenue.
2. **Improve Customer Ratings**: Focus on improving customer ratings, especially for hotels in low-performing cities. This can involve enhancing services, offering promotional packages, or upgrading facilities.
3. **Revise Pricing Strategy on the Website**: Suggest lowering prices on the hotel's website to avoid paying commission fees to third-party platforms and potentially increase direct bookings.
4. **Target Marketing for High-Performing Hotels**: Use the Pareto principle to focus marketing efforts on high-performing hotels, which could be promoted more aggressively, while underperforming hotels could benefit from specific strategies to improve performance.
5. **Expand Use of Data Analytics**: Expand data analytics within the organization for continuous monitoring and informed decision-making.

## Tools and Technologies Used
- **Power BI**: For data visualization and creating the dashboard.
- **Power Query**: For transforming and cleaning the data.


## Conclusion
This project helped AtliQ Grands make data-driven decisions, focusing on dynamic pricing, customer ratings, and pricing strategies. By leveraging business intelligence and data analytics, AtliQ Grands can enhance its operational efficiency and improve its competitive position in the luxury and business hotel market.
