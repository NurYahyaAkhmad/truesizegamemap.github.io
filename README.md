# 🗺️ Game Maps Inside Earth

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_NETLIFY_ID/deploy-status)](https://app.netlify.com/sites/YOUR_SITE_NAME/deploys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Game Maps Inside Earth** is an interactive Single Page Application (SPA) designed to help users **visualize and compare the true scale and size of popular video game maps** (such as GTA V, PUBG, Elden Ring, etc.) when overlaid onto a real-world map (using OpenStreetMap).

This project is built with a focus on performance, accuracy, and a modern **Glassmorphism** design aesthetic.

---

## ✨ Key Features

* **Accurate Scale Visualization:** Uses Leaflet.js and Geodesy principles to accurately scale game map GeoJSON data based on real-world dimensions.
* **Dynamic Map Placement:** Game maps can be added, removed, and freely **dragged and dropped** anywhere on the globe, enabling compelling comparisons (e.g., placing the Los Santos map over the New York City metropolitan area).
* **Interactive Sidebar:** A responsive sidebar featuring a modern **Glassmorphism** design, complete with **search filtering** for quick access to game data.
* **Modern UI/UX:** Implements a clean, contemporary design using CSS features like `backdrop-filter` for the transparent, blurred glass effect.
* **Mobile-Friendly:** Optimized for both desktop and mobile viewing with a toggleable sidebar control.

---

## 🛠️ Tech Stack

This is a client-side only (static) web application, relying on the following core technologies:

| Category | Technology | Purpose |
| :--- | :--- | :--- |
| **Core Mapping** | **Leaflet.js** | The leading JavaScript library for lightweight, interactive maps. |
| **Logic** | **Vanilla JavaScript (ES6)** | Manages all application logic, user interaction, and map state without reliance on large frameworks. |
| **Design** | **HTML5 / CSS3** | Structure and styling, including the implementation of CSS variables and modern layout techniques. |
| **Base Map Tiles** | **OpenStreetMap / CARTO** | Provides the real-world map layers. |

---

## 🚀 Installation and Local Setup

This project is a static web application and requires minimal setup to run locally.

### Prerequisites

You only need a modern web browser.

### Steps

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    cd YOUR_REPO_NAME
    ```

2.  **Run Locally:**
    Simply open the `index.html` file directly in your web browser. For a better development experience, it is recommended to use a local web server (such as the **Live Server** extension in VS Code).

---

## 🌐 Deployment

This project is perfectly suited for deployment on static hosting platforms.

* **Netlify:** Connect the GitHub repository; Netlify will handle the build and deploy automatically.
* **GitHub Pages:** Deploy directly from the `main` or `gh-pages` branch.

## 🤝 Contribution

Contributions are welcome! If you have suggestions for new game maps to include, bug fixes, or design improvements, please feel free to open an issue or submit a pull request.

## 📜 License

This project is licensed under the **MIT License**.
