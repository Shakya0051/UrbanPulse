# UrbanPulse – Bike-Share Mobility Analytics Dashboard

An interactive data analytics dashboard designed to explore bike-sharing usage patterns,
 identify mobility trends, and understand how weather, seasons, and day types affect bike rentals.

## 📊 Project Overview

UrbanPulse is a front-end data analytics project built to demonstrate practical data analyst skills through interactive visualizations,
 key performance indicators (KPIs), and data filtering.

The dashboard presents bike-sharing data in an easy-to-understand format, 
helping users explore rental patterns and discover insights from mobility data.

## 🎯 Project Objectives

- Analyze bike rental patterns across different seasons.
- Compare weekday and weekend usage.
- Explore the relationship between weather conditions and bike rentals.
- Display key performance indicators and trends.
- Provide interactive charts and filters for data exploration.
- Allow users to upload CSV data and export dashboard data.

## ✨ Features

- **Interactive Dashboard:** Explore bike-sharing data through visual charts.
- **KPI Cards:** View important metrics such as total rentals and average usage.
- **Dynamic Filters:** Filter data by season, day type, weather, and selected metric.
- **Data Visualizations:** Analyze trends through multiple charts.
- **CSV Upload:** Import compatible CSV datasets.
- **CSV Export:** Export data for further analysis.
- **Responsive Design:** Use the dashboard on desktop and smaller screens.
- **Snapshot Table:** Review selected data in a tabular format.

## 🛠️ Technologies Used

- **HTML5** – Dashboard structure
- **CSS3** – Styling and responsive layout
- **JavaScript** – Data processing, filters, and interactivity
- **Canvas API** – Chart rendering
- **CSV** – Data import and export

## 📁 Project Structure

```text
urbanpulse_dashboard/
│
├── index.html       # Main dashboard page
├── style.css        # Styling and responsive design
└── README.md        # Project documentation
```

## 🚀 Getting Started

### 1. Download or Clone the Project

Download the project files and place them in a folder named `urbanpulse_dashboard`.

### 2. Open the Project

Open the project folder in Visual Studio Code.

### 3. Check the File Connections

Make sure `index.html` contains the stylesheet reference:

```html
<link rel="stylesheet" href="style.css">
```

Ensure that you can also add separate  JavaScript file is linked near at the end of the HTML body:

```html
<script src="script.js"></script>
```

### 4. Run the Dashboard

You can open `index.html` directly in your browser. For a better development experience, 
use the **Live Server** extension in Visual Studio Code.

1. Open `index.html`.
2. Right-click inside the editor.
3. Select **Open with Live Server**.
4. Explore the dashboard in your browser.

## 📈 Dashboard Analysis

The dashboard is designed to help answer questions such as:

- Which seasons have higher bike rental activity?
- How does rental activity differ between weekdays and weekends?
- How do weather conditions relate to bike usage?
- Which selected metric shows the strongest usage pattern?

The displayed insights depend on the dataset loaded into the dashboard.
 If sample data is used, the results should be treated as illustrative rather than real-world findings.

## 📂 Using Your Own Dataset

1. Prepare a CSV file containing compatible bike-sharing data.
2. Use the dashboard's CSV upload feature.
3. Apply the available filters.
4. Explore the charts and KPI cards.
5. Export data if you want to analyze it further.

**Note:** Your CSV must follow the column structure expected by `script.js`. 
Check the data-loading code before importing a different dataset.

## 🌐 Deployment

The dashboard can be hosted as a static website using platforms such as:

- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)
- [GitHub Pages](https://pages.github.com/)

For deployment, upload or connect the project folder or repository and configure the hosting 
platform to serve `index.html` as the entry page.

## 💡 Future Improvements

- Connect a real bike-sharing dataset.
- Add advanced filters and date-range selection.
- Integrate a backend API for live data.
- Add predictive analytics for rental demand.
- Improve accessibility and chart tooltips.
- Add downloadable PDF reports.
- Include geographical analysis with interactive maps.

## 👨‍💻 Skills Demonstrated

This project demonstrates practical skills relevant to data analyst and front-end analytics roles:

- Data exploration and filtering
- KPI design
- Data visualization
- JavaScript programming
- CSV data handling
- Dashboard design
- Responsive web development
- Communicating insights through visual analytics

## 📄 License

This project is intended for educational and portfolio use. Add a license file if you plan to distribute the project under specific reuse terms.

---

**UrbanPulse** — Turning bike-sharing data into actionable mobility insights.
