# Superstore Sales Analytics (Power BI)

## What is this project?
I built this interactive Power BI dashboard to tackle a classic retail challenge: turning raw transactional data into something business leaders can actually use to make decisions. 

Using a Superstore dataset spanning sales across the US and Canada, the goal was to create a clean, dark-themed executive view that instantly highlights sales velocity, profitability health, and product trends over time.

---

## What the data tells us (Key Insights)
The Revenue Engines: Technology drives the massive bulk of our sales volume, with Furniture coming in a close second. 
Hidden Profit Gems: Even though Office Supplies don't bring in the massive revenue of Technology, smaller sub-categories like *Labels*, *Paper*, and *Envelopes* actually operate at the highest profit margins. On the flip side, *Storage* is heavily eating into profits with the lowest margins.
Massive Seasonality: The business has a clear cyclical rhythm. Sales spike aggressively in **March**, drop slightly in summer, pick back up in September, and hit an absolute peak during the Q4 holiday rush in November and December.

---

## Behind the Scenes (How I built it)
1. Data Prep: Cleaned and shaped the raw data using Power Query to handle data types, fix dates, and make sure filtering by country worked smoothly.
2. Modeling: Set up a clean data structure and utilized DAX measures to calculate dynamic metrics like the overall profit margin percentage.
3. UI/UX Design: Opted for a dark theme with high-contrast blue metrics to create a dashboard that is easy on the eyes but highlights critical performance metrics immediately.

---

## Take a Look

![Superstore Sales Dashboard]()

*(Feel free to download the .pbix file from this repo if you want to open it in Power BI Desktop and click through the interactive slicers yourself!)*
