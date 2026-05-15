<div align="center">

<h1>🕌 Prayer Management System</h1>

<p><i>A complete Islamic companion app — prayer times, Surahs, Duas, Tasbih counter, and more</i></p>

![Java](https://img.shields.io/badge/Java-Swing-orange?style=flat&logo=java)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Platform](https://img.shields.io/badge/Platform-Desktop-lightgrey)

</div>

---

## 📖 About the Project

The **Prayer Management System** is a Java-based desktop application built with Swing that serves as a comprehensive Islamic tool. It allows users to view real-time prayer times based on their location, read Quranic Surahs with Urdu translation, access daily Duas, count Tasbih, and explore the 99 Names of Allah (Asma-e-Husna) — all in one place.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🕐 **Real-Time Prayer Times** | Fetches live Fajr, Dhuhr, Asr, Maghrib & Isha times for any city using the AlAdhan API |
| 📖 **Surah Library** | Includes Al-Fatiha, Yaseen, Ar-Rahman, Al-Mulk, Al-Ikhlas, Al-Falak, Al-Nas, Al-Kafiron & Al-Kahf with Arabic text, Urdu translation & virtues |
| 🤲 **Daily Duas** | Collection of essential Duas for daily activities (sleeping, eating, wudu, entering/leaving home, etc.) |
| 📿 **Tasbih Counter** | Digital counter for dhikr with increment and reset functionality |
| 🧮 **Namaz Rakat Chart** | Full table of rakats for all 5 daily prayers and Jummah |
| 📋 **Asma-e-Husna** | Complete table of the 99 Names of Allah with Arabic, transliteration, and meaning |
| 👤 **User Registration** | Simple registration page with name, email, and password |

---

## 🛠️ Technologies Used

- **Language:** Java
- **GUI Framework:** Java Swing (JFrame, JPanel, JTable, JScrollPane)
- **APIs:**
  - [AlAdhan API](https://aladhan.com/prayer-times-api) — for prayer times
  - [OpenCage Geocoding API](https://opencagedata.com) — for converting city name to coordinates
- **Library:** `org.json` (JSON parsing)
- **IDE:** IntelliJ IDEA

---

## 📋 Prerequisites

Before running the project, make sure you have the following installed:

- Java JDK 8 or above
- IntelliJ IDEA (or any Java IDE)
- `json-20210307.jar` library (already included in `.idea/libraries`)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/PrayerManagementProject.git
```

### 2. Open in IntelliJ IDEA

```
File → Open → Select the PrayerManagementProject folder
```

### 3. Add the JSON Library

The project uses `json-20210307.jar`. It is already referenced in `.idea/libraries/json_20210307.xml`.
If needed, download it from [Maven Repository](https://mvnrepository.com/artifact/org.json/json/20210307) and add it manually under:

```
File → Project Structure → Libraries → Add JAR
```

### 4. Run the Application

Run the `PrayerManagementSystem.java` file:

```
src/PrayerManagementSystem.java → Right-click → Run
```

---

## 📂 Project Structure

```
PrayerManagementProject/
├── src/
│   └── PrayerManagementSystem.java    # Main application file
├── out/
│   └── production/                    # Compiled .class files
├── .idea/
│   └── libraries/
│       └── json_20210307.xml          # JSON library reference
├── PrayerManagementProject.iml
└── README.md
```

---

## 📸 App Flow

```
Welcome Screen
     ↓
Registration Page
     ↓
Navigation Menu
     ├── 📿 Tasbih Counter
     ├── 🧮 Namaz Rakat Chart
     ├── 🕐 Prayer Times
     ├── 📖 Surahs
     ├── 🤲 Duas
     └── 📋 Asma-e-Husna
```

---

## 🌐 APIs Used

| API | Purpose | Link |
|---|---|---|
| AlAdhan | Fetch daily prayer times by coordinates | https://aladhan.com |
| OpenCage | Convert city name to latitude/longitude | https://opencagedata.com |

---

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📬 Contact

**Developer:** [Your Name]
**Email:** [fatimahnasir5002@gmail.com]
**GitHub:** [@fatimahnasir](https://github.com/fatimahnasir)

---

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute it.

---

<div align="center">
  <p>Made with ❤️ for the Muslim community</p>
  <p><i>May Allah accept this effort — آمین</i></p>
</div>
