# 🌟 **Timetable to ICS File Generator — README**

## 📌 Overview

This project is a **web-based timetable generator** that allows users to create detailed exam schedules and instantly convert them into an **ICS (iCalendar) file**, which can be imported into:

* Google Calendar
* Apple Calendar (iOS/macOS)
* Microsoft Outlook
* Any calendar app supporting .ics

The goal is to provide a **simple, user-friendly interface** for generating academic or custom schedules with advanced features like auto-day detection, local storage saving, CSV export, and more.

---

## 🚀 Features

### ✅ **1. Add Unlimited Exams**

Users can create as many exam/event entries as needed.

### ✅ **2. Auto Numbering (Smart Indexing)**

* New exams always follow correct numbering.
* Delete Exam 3 → Add new exam → New one becomes **Exam 3**.

### ✅ **3. Auto Day Detection**

Selecting a date automatically fills the correct **day of the week**.

### ✅ **4. LocalStorage Save System**

Your entire timetable is saved automatically.
Page refresh hone par bhi data **restore** ho jata hai.

### ✅ **5. Error Handling**

* Missing required fields show red popup alerts
* End time < Start time validation
* Event won’t be generated unless all inputs are correct

### ✅ **6. CSV Export**

Download your timetable as a **CSV file** for sharing/storing.

### ✅ **7. Print / PDF Mode**

Built-in **Print** button lets you generate PDF directly from browser.

### ✅ **8. Reset Timetable Button**

Clears everything and creates a fresh blank Exam 1.

### ✅ **9. Beautiful Popups**

Success/error alerts appear inside a soft animated popup box.

### ✅ **10. ICS File Generator**

Creates a perfect `.ics` file with fields:

* DTSTART / DTEND
* SUMMARY (Subject Code + Subject)
* DESCRIPTION (Day, Faculty, Notes)
* LOCATION (Room)

---

## 📷 Screenshot (Add Later)

```
[ Add your project UI screenshot here ]
```

---

## 📦 Project Structure

```
/timetable-app
    ├── index.html
    ├── style.css  (optional if separated)
    ├── script.js  (optional if separated)
    └── README.md
```

All HTML, CSS, and JS can be in a **single file** or split into components.

---

## 🧠 How It Works

1. User fills exam details
2. Dates auto-convert into ICS timestamps
3. JavaScript builds ICS event blocks
4. Full `.ics` file downloads instantly
5. User can import it into any calendar app

---

## 📥 Importing the ICS File

### **Google Calendar**

1. Open Google Calendar
2. Settings → Import
3. Select your generated `.ics` file
4. Done!

### **Apple Calendar (iPhone/Mac)**

Just tap on the `.ics` file →
**Add to Calendar**

### **Windows Outlook**

Open file →
**Add Event**

---

## 🛠 Tech Stack

* **HTML**
* **CSS**
* **JavaScript**
* No backend required
* 100% client-side processing

---

## 🏆 Why This Project is Special

* No external libraries
* No server needed
* Fully offline usable
* Auto-save + error handling
* Beautiful UI
* Real-world useful tool
* Perfect for students & colleges

---

## 🎯 Future Improvements

> (Optional)
> These are features you can add later:

* Dark mode
* Theme customization
* Drag & drop exam reordering
* Multiple timetable profiles
* Export to Excel

---

## ❤️ Author

**Aashoo Sharma**
Timetable → ICS Generator WebApp
Website: *AashooSharma.tech*

---
