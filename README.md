# CineMax Movie Theatre Revenue & Operations Analytics Dashboard

An end-to-end entertainment analytics project built to evaluate multiplex box office performance, ticket sales, food and beverage revenue, show timing distribution, and seat occupancy across regional locations.

## Repository Structure
* **`dashboard`** — Contains the final Power BI executive command center file (`theatre analytics.pbix`).
* **`Datasets`** — Contains the raw and relational data sources (`Fact_Ticket_Sales`, dimension tables for movies, shows, dates, theatres, promotions, categories, customers, and screens).
* **`presentation`** — Contains project presentation slides summarizing key findings, DAX modeling strategies, and business recommendations.

## Key Highlights & Findings
* **Financial Performance:** Generated **₹6.59M** in total box office revenue alongside **₹2M** in food and beverage contributions across **18K** total tickets.
* **Peak Show Timings:** Evening and prime screening slots capture high attendance, while morning screenings maintain steady, reliable foot traffic.
* **Genre Leadership:** Action and Thriller categories lead genre distribution, contributing the highest percentage share of total revenue.
* **Operational Insights:** Seat occupancy metrics and weekday vs. weekend splits reveal optimization opportunities for show scheduling and F&B bundle promotions.

## Tools & Skills Demonstrated
* **Power BI Desktop & Advanced DAX:** Developed robust measures (`CALCULATE`, `TREATAS`, `SUMX`) and resolved complex cross-filtering challenges across a star schema data model.
* **Data Modeling:** Constructed clean relational architectures linking 9 core dimension and fact tables.
* **Executive Dashboard Design:** Built a single-page responsive command center equipped with dynamic top-header slicers (`Date`, `Booking_Channel`, `Theatre_Name`) and interactive visual tooltips.
