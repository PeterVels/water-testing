# 🧪 Water Testing Dashboard for FNQ Pools

A lightweight, mobile-friendly dashboard for visualizing pool water chemistry — no server required. Powered by HTML, JavaScript, and Google Charts. Designed and deployed from Mount Sheridan, QLD.

View it live: [petervels.github.io/water-testing](https://petervels.github.io/water-testing)

---

## 🚀 Features

- 📂 Upload any `.csv` file manually using the file chooser
- 📊 Displays 10 gauge-style charts:
  - Total Chlorine
  - Free Chlorine
  - Combined Chlorine
  - pH Level
  - Total Alkalinity
  - Cyanuric Acid
  - Total Hardness
  - Calcium Hardness
  - Phosphates
  - Total Copper
- 🖥️ 5×2 responsive layout for widescreen clarity
- 📱 Works great on mobile — tested on Android
- 🧾 Title updates dynamically based on file name

---

## 📄 CSV Format

Each line should contain a test name followed by a comma and a value. Example:
Total Chlorine,1.8 
Free Chlorine,1.7 
Combined Chlorine,0.1
pH Level,7.5
Total Alkalinity,96.33
Cyanuric Acid,44
Total Hardness,82
Calcium Hardness,82
Phosphates,0.167
Total Copper,0


Download a blank template here:  
[pool-readings.csv](https://raw.githubusercontent.com/petervels/water-testing/main/pool-readings.csv)

---

## 📱 Android Users — Getting Started

1. Use any text editor or Google Sheets to create a CSV
2. Save the file to your Downloads or Documents folder
3. Open [dashboard](https://petervels.github.io/water-testing) in Chrome
4. Scroll to bottom → tap “Choose CSV” → select your file
5. Gauges update automatically with your readings

See full guide: [Android Guide](https://petervels.github.io/water-testing/android-guide.html)

---

## 🤝 Contributions Welcome

If you have improvements, new templates, or seasonal FNQ adjustments to gauge ranges, feel free to fork the repo and submit a pull request!

---

## 🛠 Tech Stack

- HTML + CSS (responsive layout)
- JavaScript with FileReader
- Google Charts (gauge visualizations)
- GitHub Pages (hosting)

---

## 📍 Local Context

This project is tailored for pool water monitoring in Far North Queensland (FNQ). Ideal range settings align with tropical conditions, but are easily configurable in the code.

---

## 📬 Contact

Questions, suggestions, or dashboards for other regions?  
Create an issue or fork the repo to contribute.

---
