# Study Tracker App

## 🚀 Overview
The **Study Tracker App** is a console-based Java application designed to help students systematically log, track, summarize, and export their study activities. It features real-time data aggregation using advanced data structures and supports data persistence via CSV generation.

## ✨ Key Features
* **Insert Study Log:** Records study sessions tracking subject, duration, and descriptions with auto-generated timestamp.
* **In-Memory Tracking:** Maintains and renders active logs instantly from memory storage.
* **Data Aggregation:** Computes total hours dynamically, grouping summaries sorted automatically by Date or Subject.
* **CSV Export:** Saves tracking records into a formatted `MarvellousStudyTracker.csv` file for offline use.
* **Interactive CLI:** Built with a user-friendly, switch-case menu-driven loop.

## 🛠 Tech Stack
* **Language:** Java (Core Java) 
* **Collections Framework:** `ArrayList` (Dynamic Storage), `TreeMap` (Sorted Summaries) 
* **Core APIs:** `java.time.LocalDate` (Auto-Date capture), `java.io.FileWriter` (CSV Processing) 
