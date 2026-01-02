# 🚌 University Bus Tracker (Driver Client)

[![English](https://img.shields.io/badge/Language-English-blue)](#-english-section) [![Persian](https://img.shields.io/badge/Language-Persian-green)](#-بخش-فارسی)

---

<div id="english-section"></div>

## 🇬🇧 English Section

A lightweight, dependency-free frontend web application designed to track university buses in real-time. This specific repository contains the **Driver's Panel**, which utilizes the device's GPS to capture location data and visualize it on an interactive map.

### ✨ Features

* **Zero Dependencies (No NPM):** Runs directly in the browser. No `npm install`, build steps, or bundlers required.
* **Real-time GPS Tracking:** Uses HTML5 `navigator.geolocation.watchPosition` for accurate tracking.
* **Interactive Map:** Built with [Leaflet.js](https://leafletjs.com/) (loaded via CDN).
* **Visual Feedback:**
    * Custom bus icon.
    * Real-time path tracing (red line).
    * GPS accuracy indicator (blue circle).
* **Error Handling:** Displays user-friendly messages for GPS permission errors or connectivity issues.

### 🛠 Tech Stack

* **HTML5**
* **CSS3** (Responsive & Single-file architecture)
* **JavaScript** (ES6+)
* **Leaflet.js**

### 🚀 How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/university-bus-tracker.git](https://github.com/your-username/university-bus-tracker.git)
    ```
2.  **Open the file:**
    Simply open `index.html` (or `driver.html`) in any modern web browser.

> **⚠️ Important Note regarding GPS:**
> Modern browsers enforce security policies for the Geolocation API. To access the GPS, the file must be served via **HTTPS** or **Localhost**. It might not work if you just open the file path (`file://...`) on mobile devices.

### 🗺 Roadmap

* [ ] Integrate **Socket.io** to emit location data to a backend server.
* [ ] Create a Student View (Receiver) to listen for coordinates.
* [ ] Add backend persistence for trip history.

---

<div id="persian-section"></div>

## 🇮🇷 بخش فارسی

این پروژه، نسخه کلاینت (Frontend) یک سامانه سبک و سریع برای ردیابی سرویس‌های اتوبوس دانشگاه است.
این مخزن مشخصاً شامل **پنل راننده** است که با استفاده از GPS گوشی هوشمند، موقعیت مکانی لحظه‌ای را دریافت کرده و روی نقشه نمایش می‌دهد (آماده اتصال به بک‌‌اند).

### ✨ ویژگی‌ها

* **بدون وابستگی (No NPM):** اجرای مستقیم روی مرورگر بدون نیاز به نصب پکیج یا بیلد گرفتن.
* **ردیابی دقیق GPS:** استفاده از `watchPosition` برای دریافت موقعیت لحظه‌ای و دقیق.
* **نقشه تعاملی:** استفاده از کتابخانه قدرتمند [Leaflet.js](https://leafletjs.com/).
* **نمایش بصری:**
    * آیکون سفارشی اتوبوس.
    * رسم مسیر طی شده روی نقشه (خط قرمز).
    * نمایش دایره دقت GPS (Accuracy Circle).
* **مدیریت خطا:** نمایش پیام‌های وضعیت فارسی در صورت قطع شدن GPS یا عدم صدور مجوز.

### 🛠 تکنولوژی‌های استفاده شده

* **HTML5**
* **CSS3** (ریسپانسیو)
* **JavaScript** (ES6+)
* **Leaflet.js**

### 🚀 نحوه اجرا

۱. **کلون کردن مخزن:**
   ```bash
   git clone [https://github.com/your-username/university-bus-tracker.git](https://github.com/your-username/university-bus-tracker.git)
