# 🏛️ Barangay Tinapian — Business Permit Tracker

> A fully offline, single-file web application for managing business permits in **Barangay Tinapian, Manito, Albay**. Built with pure HTML, CSS, and JavaScript — no internet connection or server required.

---

## 📌 Overview

The **Barangay Business Permit Tracker** is a lightweight, browser-based tool designed to help barangay officials and staff efficiently monitor, manage, and track business permits within their jurisdiction. It was built with simplicity in mind — just open the HTML file in any browser and it works immediately.

This project was built as part of my personal portfolio to demonstrate practical, real-world front-end development that directly addresses the needs of local government units (LGUs) in the Philippines.

---

## ✨ Features

- **Dashboard Summary** — At-a-glance count of Active, Expiring, and Expired permits
- **Permit Cards** — Each business displayed as a clean card with all relevant details
- **Status Badges** — Automatically calculated status (Active / Expiring / Expired) based on today's date
- **Expiry Alerts** — Highlighted warning section for permits expiring within 30 days or already expired
- **Search** — Filter permits by business name, owner name, or permit number
- **Status & Type Filters** — Narrow down permits by status or business category
- **Add / Edit / Delete** — Full CRUD operations with form validation
- **Duplicate Detection** — Prevents duplicate permit numbers from being saved
- **Excel Auto-Save** — Automatically downloads an updated `.xlsx` file after every change
- **Load from Excel** — Import permit records back from a previously saved Excel file
- **Export CSV** — One-click export of all permit data as a `.csv` file
- **Excel Summary Sheet** — Downloaded Excel includes a Summary tab with permit counts
- **Persistent Storage** — Data saved in browser `localStorage` between sessions
- **Responsive Design** — Works on desktop, tablet, and mobile browsers
- **100% Offline** — No backend, no database, no internet needed

---

## 🖥️ Screenshots

- [Desktop View](images)  
- [Phone View](images/)  
---

## 🚀 How to Use

1. **Download** the [permit-tracker.html](permit-tracker.html) file from this repository
2. **Open** it in any modern web browser (Chrome, Firefox, Edge, Safari)
3. The app loads with sample data automatically on first use
4. Click **＋ New Permit** to add your first real permit
5. Every change **auto-saves** to an Excel file (`.xlsx`) downloaded to your computer
6. To reload your data next time, click **📂 Load Excel** and select your saved file

> ⚠️ **Note:** Because this app is fully offline, data is stored in your browser's local storage. To avoid data loss, always keep a copy of your exported Excel file as your backup.

---

## 📁 Repository Contents

| File | Description |
|---|---|
| [permit-tracker.html](permit-tracker.html) | The complete application — single HTML file, no dependencies to install |
| [Barangay_Tinapian_Permits_99.xlsx](Barangay_Tinapian_Permits_99.xlsx) | Synthetic test dataset with 99 business permit records |
| [README.md](README.md) | This file |

---

## 🖼️ Preview Screenshot
![Dashboard View](images)


---

## 🛠️ Technology Stack

| Technology | Usage |
|---|---|
| HTML5 | App structure and layout |
| CSS3 | Styling, animations, responsive design |
| Vanilla JavaScript | All logic, filtering, CRUD, and storage |
| [SheetJS (xlsx.js)](https://sheetjs.com/) | Excel file reading and writing (loaded via CDN) |
| Google Fonts | Sora + IBM Plex Mono typefaces |
| Browser localStorage | Client-side data persistence |

> No frameworks. No build tools. No installation. Just one file.

---

## 📊 Sample Dataset

The repository includes **`Barangay_Tinapian_Permits_99.xlsx`** — a **synthetic test dataset** with 99 sample business permits.  
⚠️ **Note:** This dataset is for testing and demonstration purposes only. It does not represent actual barangay records.

Features of the dataset:
- Authentic-style Filipino business names (Sari-sari stores, Carinderia, Bakeries, Hardware stores, etc.)
- Realistic Filipino owner names with middle initials
- Purok and street addresses within Barangay Tinapian, Manito, Albay
- Mixed permit statuses — Active, Expiring, and Expired records
- Permit numbers in the format `TP-YYYY-###`
To load it into the app, click [📂 Load Excel](Barangay_SanJose_Permits_99.xlsx) and select the file.

---

## 💡 What I Learned / Built

This project gave me hands-on experience with:

- Building a complete CRUD application in vanilla JavaScript without any framework
- Reading and writing `.xlsx` Excel files directly in the browser using SheetJS
- Designing a clean, professional UI using only CSS (no UI libraries)
- Implementing real-time search, filtering, and sorting
- Working with browser `localStorage` for offline data persistence
- Solving a real government/community problem with simple technology

---

## 🔮 Possible Future Improvements

- [ ] Print-friendly permit certificate generator
- [ ] SMS or email reminder integration for expiring permits
- [ ] Multi-barangay support
- [ ] Renewal tracking and payment history
- [ ] QR code generation per permit
- [ ] Cloud sync via Google Sheets API
- [ ] Admin login / password protection

---

## 👤 Author

**[Your Name Here]**
- GitHub: [@trillesgian29-cpu](https://github.com/trillesgian29-cpu)
- Portfolio: [yourportfolio.com](https://github.com/trillesgian29-cpu/MyyPortfolio.git)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

> 💬 *Built to serve the community of Barangay Tinapian, Manito, Albay — and as a demonstration of what simple web technology can do for local governance. Dataset included is for testing only.*
This project demonstrates how AI applications can be applied to community governance, making record management more transparent, organized, and scalable.
