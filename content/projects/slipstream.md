---
title: Slipstream
disableshare: true
summary: 
draft: false
hidemeta: false
weight: 14
---

The **Slipstream** project is a Formula 1 database visualizer designed to make race data, driver statistics, team performance, and circuit information more accessible and engaging. Built on PostgreSQL with interactive visualizations, it provides fans and analysts with data-driven insights into Formula 1 history and performance.

## Core Capabilities

- **Race & Season Exploration**: Search and view details of past races by year and venue, including winners, podium finishers, and full results.  
- **Driver & Team Stats**: Look up performance statistics such as wins, podiums, points, and season rankings.  
- **Interactive World Map**: Explore global F1 circuits plotted on a map with coordinates, tooltips, zoom, and click-to-navigate functionality.  
- **Position Distribution**: Visualize how often a driver finishes in each position across all races, highlighting performance consistency.  
- **Circuit Profiles**: Dive into track-specific insights such as historical winners, top constructors, and all past races at that venue.  

## Technologies Used

- **PostgreSQL**: Backend database storing races, results, drivers, constructors, and circuit data.  
- **Python / Flask**: Backend service for handling routes and database queries.  
- **D3.js**: Frontend visualization library powering position distribution histograms and interactive circuit maps.  
- **HTML, CSS, JavaScript**: For frontend rendering and user interaction.  

## Database Design & Queries

- **Driver Pages**: Aggregate queries compute podium finishes, wins, laps driven, and best performances for each driver.  
- **Circuit Pages**: SQL joins and grouping identify dominant constructors and drivers at each track, with historical race listings.  
- **Relaxed Constraints**: Adjustments were made to account for real-world edge cases, such as drivers not finishing (`NULL` position) or starting from the pit lane (`Grid = 0`).  

## Related Links

- [GitHub Repository](https://github.com/vishruthdevan/slipstream)
