# Supply_Atlas3D

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

**[🌐 View Live Demo](https://mendeltem.github.io/Supply_Atlas3D/)**

Supply_Atlas3D is a browser-based, interactive 3D globe designed as an educational simulation tool[cite: 1]. It visualizes macroeconomic data and global supply chains by allowing users to explore the trade profiles, demographics, and natural resources of countries worldwide[cite: 1].

## 🌍 Core Features

*   **Interactive 3D Environment:** Orbit, zoom, and explore a dynamically rendered 3D Earth surrounded by a custom starfield[cite: 1].
*   **Macroeconomic Profiles:** Hover over any nation to view a detailed tooltip displaying its flag, geographic region, total land area, population, and GDP metrics[cite: 1].
*   **Supply Chain & Trade Data:** Understand international trade through explicitly listed top exported and imported commodities for each country[cite: 1].
*   **Dynamic Resource Filtering:** Isolate specific raw materials and high-tech commodities (e.g., crude oil, gold, copper, integrated circuits, wheat) using a built-in dropdown menu[cite: 1]. The map dynamically highlights countries based on their export ranking for the selected material[cite: 1].
*   **Customizable UI Overlays:** Toggle country borders, a latitude/longitude graticule, a day/night terminator shadow, and auto-rotation[cite: 1].

## 💻 Technical Stack

The application is lightweight and contained entirely within the frontend, utilizing:
*   **HTML5 `<canvas>`** for rendering the interactive globe and starfield[cite: 1].
*   **D3.js (v3.5.17)** for geographic projections and path generation[cite: 1].
*   **TopoJSON & Datamaps** for rendering geographical boundaries and mapping economic datasets to spherical coordinates[cite: 1].

## 🚀 Local Installation & Usage

Since this is a client-side application, no complex build steps or server environments are required.

1. Clone the repository:
   ```bash
   git clone [https://github.com/mendeltem/Supply_Atlas3D.git](https://github.com/mendeltem/Supply_Atlas3D.git)