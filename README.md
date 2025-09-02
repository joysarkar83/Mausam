# 🌤️ Mausam  

A **Kotlin-based weather app** that fetches real-time data from the **OpenWeatherMap API**.  
**Mausam** (meaning *"weather"* in Hindi) delivers current conditions—temperature, humidity, wind speed, and sunrise/sunset—alongside **dynamic animations** that mirror the actual sky (sunny, cloudy, rainy, etc.).  
City-based search ensures an interactive and user-friendly experience.  

---

## ✨ Features
- 📡 Real-time display of:
  - **Temperature**, **Humidity**, **Wind Speed**, **Sunrise / Sunset**  
- 🎬 **Animated backgrounds** matching current weather (sunny, cloudy, rainy, etc.)  
- 🔍 **City search functionality** for localized weather updates  
- 🖥️ Clean & intuitive **UI** for a seamless user experience  

---

## 🛠️ Tech Stack
- **Kotlin**  
- **Android** (Jetpack components assumed)  
- **Gradle (Kotlin DSL)** as the build system  

---

## 📂 Project Structure
```
Mausam/
│-- .idea/ # IDE configs (Android Studio)
│-- app/ # App source code
│-- gradle/ # Gradle wrappers
│-- build.gradle.kts # Gradle build config
│-- settings.gradle.kts # Project settings
│-- gradlew / gradlew.bat # Gradle wrapper scripts
│-- gradle.properties
│-- Mausam.apk # Prebuilt APK (for direct install)
│-- README.md # Project overview (this file)
```

---

## 🚀 How to Use
1. **Clone the repository**
```
git clone https://github.com/joysarkar83/Mausam.git
cd Mausam
```
2. **Run via Android Studio**  
- Open the project in Android Studio  
- Sync Gradle  
- Run on a connected device or emulator  

# OR

**Install APK directly**  

---

## 📚 What I Learned
- 🔗 Integrated a **live API (OpenWeatherMap)** in a real-world mobile app  
- 🎨 Designed a UI that **dynamically reflects weather data with animations**  
- 📦 Built & packaged an Android app, gaining hands-on experience with **Kotlin + Gradle workflows**  

---

## ⚠️ Limitations
- 🌐 Requires **active internet connection** (no offline caching)  
- 🎬 Animations are **purely visual**; limited offline functionality  
- 🧩 Currently an **MVP** with minimal error handling and **no localization**  

---

## 🚧 Next Steps
- ✨ Add **error handling** for API/network failures  
- 💾 Implement **offline caching** (e.g., Room DB, SharedPreferences)  
- 🌍 Expand UI with:
- Multiple cities support  
- Daily forecast view  
- 🌐 Refactor for **localization** and multi-device responsiveness  

---

## 📝 Notes
⚠️ This project is **for learning/practice purposes only**.  
All trademarks, brands, and design inspirations belong to their rightful owners.  
