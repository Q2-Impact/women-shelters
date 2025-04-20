---
title: "Women Shelter Map - Q2 Impact"
output: github_document
---

# Women Shelter Locator Web App

This interactive map shows women's shelters across the United States, categorized by their current operational status:  
- 🟢 Open  
- 🔴 Closed  
- 🔵 Unknown  

Hosted at: [https://q2-impact.github.io/women-shelters](https://q2-impact.github.io/women-shelters)

## 🚀 Features

- **Searchable** by shelter name, type, or location (city/state/ZIP)
- **Color-coded markers**:
  - 🟢 Green: Open shelters
  - 🔴 Red: Closed shelters
  - 🔵 Blue: Unknown status
- **Popups** with shelter name, hours, contact info, address, and website
- **Geolocation** to center the map near your current location
- **Distance-based ranking** for closest shelters
- **Satellite map view** for better navigation context

## 🧠 Technologies Used

- **[Leaflet.js](https://leafletjs.com/)** – for interactive map rendering  
- **QGIS + qgis2web** – to export spatial layers  
- **HTML + JavaScript** – customized layout and behavior  
- **GitHub Pages** – for free static hosting  
- **Custom JSON dataset** – shelter metadata and coordinates  

## 📁 File Structure

- `index.html` – main map application  
- `full_shelter_data_v6_1.js` – GeoJSON data containing shelter properties  
- `/css` and `/js` – styling and scripts for map controls, icons, popups  
- Hosted via `gh-pages` branch on the GitHub organization `Q2-Impact`

## 📦 Dataset Fields (Sample)

Each shelter contains fields like:
- **Name**  
- **Address, City, State**  
- **Phone, Website, Email**  
- **Open Hours** (per day)  
- **Open State** (Open, Closed, Unknown)  
- **Type** (Shelter, Non-Profit, Social Services, etc.)

## 🏁 How to Use

1. Open the [map link](https://q2-impact.github.io/women-shelters)  
2. Use the search bar 🔍 to find shelters near you  
3. Click any dot to see detailed shelter info  
4. Use zoom/pan tools to explore the map  

