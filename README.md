# 🌍 World Clock & Time Zone Converter

A modern, responsive, and highly interactive web app that lets you view, compare, and plan across multiple time zones — perfect for travelers, remote teams, and global collaborators.  

Includes a **Meeting Planner**, **Reference Time Converter**, customizable business hours, drag-and-drop reordering, and theme switching between a relaxing **Starry Dark Mode** and **Bubbly Light Mode**.

---

## ✨ Features

### 🕒 Real-Time Local Clock
- Displays **current local time** with live second updates.
- Shows **full date**, **timezone name**, and **GMT offset**.
- Dynamic status indicators for:
  - **Business Hours**
  - **After Hours**
  - **Weekend**

### 🌏 Time Zone Management
- Search and add time zones by **city** or **country**.
- Displays:
  - Local time
  - Date
  - GMT offset
  - Daylight Saving Time (DST) indicator
- **Drag & Drop** to reorder cards.
- Inline editing of timezone labels.
- Filter by **business hours**, **after hours**, or **weekends**.

### 📅 Reference Time Conversion
- Select a **specific date & time** to use as a reference point.
- Instantly see what that time is in all tracked zones.
- Easily **reset to current local time**.

### 📊 Meeting Planner
- Visual time grid for all tracked zones.
- Adjustable:
  - Date
  - Meeting duration
  - Time interval (15, 30, or 60 minutes)
- Drag meeting block across the grid to find the best fit.
- Color-coded business and non-business hours.

### ⚙️ Customization & Settings
- Choose **12-hour** or **24-hour** clock format.
- Customize default **business hours**.
- **Auto Timezone Sync**:
  - Detects if your local timezone changes.
  - Updates automatically at a chosen interval.

### 🎨 Themes & Visuals
- **Dark Mode**: Starry animated background.
- **Light Mode**: Animated bubbly gradient background.
- Smooth UI animations & accessible controls.

### 💾 Persistent Data
- All preferences, added time zones, and settings are saved in **localStorage**.
- Your setup is preserved between visits.

---

## 📂 Project Structure

```
index.html       # Main HTML structure
style.css        # Responsive and theme-based styling
main.js          # Core application logic and interactions
luxon.min.js     # Time & date handling
timezoneData.js  # Timezone data list
Sortable.min.js  # Drag-and-drop functionality
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/world-clock-timezone-converter.git
cd world-clock-timezone-converter
```

### 2️⃣ Open in Browser
Simply open `index.html` in your browser.

> 💡 For best performance, host it on a web server (e.g., GitHub Pages, Netlify, Vercel, or Cloudflare Pages).

---

## 🔧 Usage Guide

1. **View Local Time**  
   Your current time is displayed automatically at the top.

2. **Add Time Zones**  
   - Type a city or country in the search box.
   - Click **Add Time Zone** to create a card.

3. **Reorder & Edit**  
   - Drag cards to reorder.
   - Click the pencil icon to rename.

4. **Plan Meetings**  
   - Open the Meeting Planner.
   - Adjust date, duration, and time interval.
   - Drag the blue meeting block to find the optimal slot.

5. **Customize Settings**  
   - Open **Settings** to adjust:
     - Time format
     - Business hours
     - Auto timezone sync

---

## 🌐 Deployment

This app is **static** (HTML/CSS/JS) — no backend required.

You can deploy to:
- **GitHub Pages**: Push to `main` branch → Settings → Pages → Select branch.
- **Netlify / Vercel**: Drag & drop the folder.
- **Cloudflare Pages**: Link GitHub repo and deploy.

---

## 📜 License
This project is licensed under a custom license. Please refer to the `LICENSE` file for details.
