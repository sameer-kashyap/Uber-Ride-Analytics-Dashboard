# Uber Ride Analytics Dashboard

This project is a comprehensive analysis of Uber's ride-hailing operations, built from a detailed set of business requirements. The primary goal was to create a centralized, interactive Power BI dashboard to help stakeholders track KPIs and identify trends across bookings, revenue, riders, and vehicle performance.

The dashboard consolidates scattered data into a single source of truth, featuring dynamic page navigation, a collapsible filter panel, and detailed drill-downs.

---

## 🚀 Key Interactive Features

This report was designed to be highly interactive and user-friendly:

* **Multi-Page Analysis:** A responsive **visual slicer** is used to navigate between 5 distinct report pages, allowing for a seamless user experience that works well on different screen sizes.
* **Collapsible Filter Panel:** A "hide-and-show" bookmark button (on the top-right) maximizes report space while providing powerful filtering options (by Vehicle, Payment Method, etc.).
* **Drill-Downs & Cross-Filtering:** All visuals on each page are interconnected, allowing users to click on any data point (e.g., a vehicle type or a month) and see the entire report filter in real-time.

---

## 🗂️ Dashboard Pages & Analysis

The dashboard is broken down into 5 key sections, accessible via the main navigation slicer.

### 1. Overview

Provides a high-level executive summary of all core KPIs.
* **KPIs:** Completed Bookings, Lost Bookings, Total Revenue, Total Distance, Avg. Distance, Avg. Rider Rating, Avg. Driver Rating.
* **Charts:**
    * Monthly & Quarterly Analysis (Bookings & Revenue)
    * Revenue by Vehicle Type
    * Top Drop-off & Pick-up Locations

### 2. Vehicle

Deep-dives into vehicle-specific performance.
* **Charts:**
    * Detailed information by Vehicle (Booking Count, Revenue, Contribution %)
    * Ride Status by Vehicle
    * Bookings & Revenue by Vehicle Type

### 3. Revenue

Analyzes all financial metrics and payment methods.
* **Charts:**
    * Revenue by Customer & Vehicle
    * Revenue by Payment Method
    * Monthly & Quarterly Revenue Trends

### 4. Rider

Focuses on rider behavior and segmentation.
* **Charts:**
    * Cancel Rides by Reason
    * Rider Status by Payment Method
    * Rider Segmentation (First Rider, Return Rider, Regular Rider)

### 5. Location

Analyzes geographic and time-based trends.
* **Charts:**
    * Monthly Total Distance
    * Total Distance by Vehicle
    * Busy Time Slots (Heatmap)
    * Busy Areas (Map)

---

## 🛠️ Tech Stack

* **Data Visualization:** **Power BI**
* **Data Modeling & Analysis:** **DAX** (Data Analysis Expressions)
    * Used to create all core measures (Completed Booknings, Revenue, etc.).
    * Used to implement bookmarking and selection logic for the responsive page navigation and the collapsible filter panel.
