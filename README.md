# FinBoard Premium

![FinBoard Dashboard](https://img.shields.io/badge/Status-Active-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

**FinBoard** is a premium, high-performance financial dashboard designed to provide real-time market data, portfolio management, and advanced financial analytics. Built with modern UI/UX principles, it features a sleek glassmorphism design, neon accents, and a responsive layout that feels like a native mobile app.

[**🔗 View Live Demo**](https://mariakotov.github.io/fintech-portfolio-dashboard)

---

## 🚀 Key Features

*   **Real-Time Data Integration**: Fetches live market quotes and historical data directly from Yahoo Finance via a CORS proxy.
*   **Advanced Analytics & Risk Score**: Features a dynamic Risk Score gauge that calculates the annualized volatility (Standard Deviation) of market benchmarks (like SPY) in real-time.
*   **Interactive Performance Charts**: High-performance line and sparkline charts built with Chart.js, utilizing premium gradients and smooth animations to track portfolio value and asset history.
*   **Premium UI/UX Design**: 
    *   **Glassmorphism Theme**: Frosted glass panels with deep navy backgrounds and neon highlights.
    *   **Responsive Architecture**: A floating sidebar for desktop users and a native-app-like bottom navigation bar for mobile users.
    *   **Modern Typography**: Utilizes `Outfit` for readability and `Space Grotesk` (monospace) for precise financial figures.
*   **Comprehensive Views**: Includes dedicated pages for Portfolio Management, Market Discovery (Heatmaps), and Data Extraction.

---

## 🛠️ Tech Stack

*   **Frontend**: HTML5, Vanilla JavaScript (ES6+)
*   **Styling**: [Tailwind CSS](https://tailwindcss.com/) (via CDN with custom configurations)
*   **Layouting**: Advanced CSS Flexbox and CSS Grid
*   **Data Visualization**: [Chart.js](https://www.chartjs.org/) (Doughnut, Line, Sparklines)
*   **API / Data Source**: Yahoo Finance API (Proxied via AllOrigins) & Google Apps Script
*   **Icons & Assets**: Inline SVG icons and DiceBear Avatars

---

## 🏁 Getting Started

To run this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/mariakotov/fintech-portfolio-dashboard.git
    ```
2.  **Navigate to the directory:**
    ```bash
    cd fintech-portfolio-dashboard
    ```
3.  **Run the application:**
    Since this is a front-end only application without a build step, you can simply open the `index.html` file in your preferred web browser:
    ```bash
    # On macOS
    open index.html
    ```
    *Note: Due to browser security restrictions (CORS) when opening files directly via `file://`, the Yahoo Finance API requests are routed through a public CORS proxy. For production environments, it is recommended to serve the files using a local web server (e.g., `npx serve`, or VS Code Live Server).*

---

## 👩‍💻 Author

**Maria Kotov**  
Information Systems & Business Administration Student | Tech Operations Professional  
Focusing on data-driven systems and functional digital solutions.

[LinkedIn](https://www.linkedin.com/in/maria-kotov-005116269/) | [GitHub](https://github.com/mariakotov)

---
*Crafted with precision for modern information systems.*
