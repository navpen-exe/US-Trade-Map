# US Foreign Trade, 2024
A webmap showing:
 - The balance of trade between the US and every other country^1^
 - The most traded goods with each country

&ensp;&ensp;^1^ and also certain territories, such as the Indian Ocean Territories (both Australian and British), Hong Kong & Macau, etc.

## 📌 Project Overview
- Visualize US trade balances, on a global as well as individual country basis
- Give information on what goods are being traded with which countries (Top 3 imports and exports)

## 🛠️ Tools
- Leaflet.js - Web mapping JavaScript library
- QGIS - Analyzing and editing GeoJSON files
- Excel - Analyzing and processing trade data
- Bootstrap - Building the page layout

## 📋 Data Sources
- Trade Data - [US International Trade Commission](https://dataweb.usitc.gov)
- Country Border Data - [Natural Earth](https://www.naturalearthdata.com)

## 📂 File Structure
<code>
project-folder/ <br/>
├── index.html # Main web page <br/>
├── data/ <br/>
│   ├── Country-Boundaries.geojson # Country Border Data<br/>
│   └── Import-Export-Totals.json # Total trade with each country (for shading) <br/>
│   └── Trade-Categories.json # Top trade category for each country (when clicked) <br/>
└── README.md # This file
</code>

## 📰 Inspiration
As this was a class assignment, I was supposed to pick a news article, and use that as inspiration for the map I would make. When I started brainstorming ideas, it was just after Trump's tariffs had been announced. So I don't really have a single news article, as basically every news outlet was covering it. But, here are some relevant ones:
- [CNN](https://www.cnn.com/2025/04/02/business/liberation-day-trump-tariffs)
- [BBC](https://www.bbc.com/news/articles/c0qnd2x1nn3o)
- [CBS](https://www.cbsnews.com/news/trump-liberation-day-new-tariffs-us/)
- [NPR](https://www.npr.org/2025/04/02/nx-s1-5345802/trump-tariffs-liberation-day)