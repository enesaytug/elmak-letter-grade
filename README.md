# ELK356E ELMAK · Letter Grade Estimation Simulator

A beautifully designed, interactive web-based simulator to estimate your final letter grade and percentile for the **ITU ELK356E Electrical Machines** course. 

Check out the live version: [ELMAK Letter Grade Simulator](https://enesaytug.github.io/elmak-letter-grade/)

## 🚀 Features

- **Interactive Sliders**: Easily input your Quiz and Midterm grades using modern, responsive sliders.
- **Live Estimation**: See how your final exam score affects your overall weighted average and estimated letter grade in real-time.
- **Data-Driven Probability**: Instead of using standard absolute grading, the estimations are based on the **actual 2025-2026 Spring term histogram**.
- **Visual Analytics**: 
  - **Probability Density (KDE)**: A smooth continuous curve generated from discrete data using Gaussian Kernel Density Estimation to show exactly where you stand among your peers.
  - **Raw Histogram**: View the original discrete student distribution data used to calculate the curve.

## 🛠️ Built With

- **HTML5 & Vanilla CSS**: For a clean, modern, and dependency-free UI with premium typography (Fraunces & DM Sans).
- **Vanilla JavaScript**: Handles all the real-time math, statistics, and KDE logic without heavy frameworks.
- **Chart.js**: Powers the elegant charts rendering the KDE probability density and the raw histogram.

## 📂 Usage / Installation

Since this is a static client-side web application, you don't need any complex build steps or servers to run it locally:

1. Clone or download this repository.
2. Open the `index.html` file in any modern web browser.
3. Adjust the sliders with your grades and explore the charts!

---
*Developed for ITU Students.*
