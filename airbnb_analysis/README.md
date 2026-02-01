# Airbnb Market Analysis: Columbus vs New York

## Author
[Caroline Monahan]

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to [help travelers understand the differences in pricing, availability, and other listing characteristics to make more informed decisions while booking an Airbnb in Columbus or New York City].

## Research Questions

1. [Is room type related to variance in price in both Columbus and New York City?]
2. [Which room types have the highest availability in Columbus and New York City throughout the year?]
3. [Which neighborhoods in Columbus and New York City give the most access to an entire home/apt?]
4. [Do listings with more flexible minimum night requirements offer different room types/price ranges in Columbus compared to New York City?]
5. [Are listings with more review activity concentrated by room_type or neighborhood in either city?]

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | [Is room type related to variance in price in both Columbus and New York City?] | [room_type, price] | [listings.csv, listings(1).csv] | [Structured] |
| 2 | [Which room types have the highest availability in Columbus and New York City throughout the year?] | [room_type, availability] | [listings.csv, listings(1).csv] | [Structured] |
| 3 | [Which neighborhoods in Columbus and New York City give the most access to an entire home/apt?] | [neighbourhood, room_type] | [listings.csv, listings(1).csv] | [Structured] |
| 4 | [Do listings with more flexible minimum night requirements offer different room types/price ranges in Columbus compared to New York City?] | [minimum_nights, room_type, price] | [listings.csv, listings(1).csv] | [Structured] |
| 5 | [Are listings with more review activity concentrated by room type or neighborhood in either city?] | [number_of_reviews, room_type, neigbourhood] | [listings.csv, listings(1).csv] | [Structured] |

## Data Overview
- **Columbus, Ohio:** [2877] listings (as of Sept 26, 2025)
- **New York City:** [36261] listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created
