# 📊 Interactive Data Analytics Dashboard

A fully responsive **Data Analytics Dashboard** built using **React.js**, **Chart.js**, and **PapaParse**. This project enables users to upload any CSV dataset and instantly visualise it through interactive Line, Bar, and Pie charts — with filtering, sorting, and KPI cards.

---

## 🚀 Live Demo

> [Click here to view live on GitHub Pages](https://YOUR-GITHUB-USERNAME.github.io/data-analytics-dashboard)

---

## 🖼️ Features

| Feature | Description |
|---|---|
| 📁 CSV Upload | Upload any CSV file and the dashboard auto-detects columns |
| 📈 Line Chart | Trend analysis over time with smooth curves |
| 📊 Bar Chart | Category comparison with dynamic color coding |
| 🥧 Pie Chart | Proportional distribution view |
| 🔢 KPI Cards | Auto-computed Total, Average, and Peak values |
| 🔍 Range Filter | Filter data between any two rows/months |
| 🗂️ Sortable Table | Click any column header to sort ascending/descending |
| 📱 Responsive | Works on mobile, tablet, and desktop |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **React.js 18** | Component-based UI framework |
| **Chart.js 4 + react-chartjs-2** | Interactive chart rendering |
| **PapaParse** | Fast in-browser CSV parsing |
| **React Hooks** (useState, useCallback) | State management |
| **CSS3 / Flexbox / Grid** | Responsive layout |
| **GitHub Pages** | Free deployment |

---

## 📁 Project Structure

```
data-analytics-dashboard/
│
├── public/
│   ├── index.html          # Main HTML template
│   └── sample-data.csv     # Sample dataset (Sales/Revenue)
│
├── src/
│   ├── components/
│   │   ├── Header.js       # Top navigation bar + CSV upload button
│   │   ├── Header.css
│   │   ├── KPICards.js     # Summary metric cards (Total, Avg, Peak)
│   │   ├── KPICards.css
│   │   ├── FilterBar.js    # Date/row range filter dropdowns
│   │   ├── FilterBar.css
│   │   ├── LineChart.js    # Trend line chart (Chart.js)
│   │   ├── BarChart.js     # Bar chart (Chart.js)
│   │   ├── PieChart.js     # Pie/donut chart (Chart.js)
│   │   ├── DataTable.js    # Sortable data table
│   │   └── DataTable.css
│   │
│   ├── App.js              # Root component — state management + layout
│   ├── App.css             # Global layout styles
│   ├── index.js            # React entry point
│   └── index.css           # Body/reset styles
│
├── package.json            # Dependencies and scripts
└── README.md               # Project documentation
```

---

## ⚙️ How to Run Locally

### Prerequisites
- Node.js (v16 or above)
- npm

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/YOUR-GITHUB-USERNAME/data-analytics-dashboard.git

# 2. Navigate into the project
cd data-analytics-dashboard

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
```

The app will open at `http://localhost:3000`

---

## 🌐 Deploy to GitHub Pages

```bash
# 1. In package.json, update "homepage":
#    "homepage": "https://YOUR-GITHUB-USERNAME.github.io/data-analytics-dashboard"

# 2. Install gh-pages
npm install gh-pages --save-dev

# 3. Deploy
npm run deploy
```

Your app will be live at `https://YOUR-GITHUB-USERNAME.github.io/data-analytics-dashboard`

---

## 📂 How to Use

1. **Open the dashboard** — it loads with built-in sample sales data
2. **Upload your own CSV** — click "Upload CSV" (top right) and select any `.csv` file
3. **Select a metric** — click buttons (Sales / Revenue / Customers / Returns) to switch charts
4. **Filter range** — use the "From" and "To" dropdowns to focus on a date range
5. **Sort the table** — click any column header to sort ascending or descending

### CSV Format
Your CSV file should have:
- First column: **labels** (e.g., Month, Date, Category)
- Remaining columns: **numeric values** (e.g., Sales, Revenue, Users)

```csv
Month,Sales,Revenue,Customers
January,120,45000,98
February,145,52000,112
...
```

---

## 🧠 Concepts Demonstrated

- **React Hooks** — `useState`, `useCallback` for efficient state and event handling
- **Component Architecture** — Reusable, single-responsibility components
- **Props Drilling** — Controlled data flow from `App.js` to child components
- **CSV Parsing** — Real-time file reading with PapaParse
- **Chart.js Integration** — Dynamic datasets with responsive chart options
- **Conditional Rendering** — Charts update instantly on filter/metric change
- **Responsive Design** — CSS Grid + Flexbox, mobile-first layout

---

## 👩‍💻 Author

**Sushma Rani Kommireddy**  
B.Tech — Artificial Intelligence & Machine Learning (2024)  
📧 sushmaranikommireddy@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/kommireddysushmarani/)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
