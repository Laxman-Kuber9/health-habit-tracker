# health-habit-tracker
This is a web-based application developed to help users track their daily health habits and monitor their progress. It includes features like habit logging, a user dashboard, and data visualization.  Tech Stack: PHP, MySQL, HTML, CSS, JavaScript.
# 🚀 HabitQuest - Gamified Health & Habit Tracker

**HabitQuest** is an advanced, gamified Progressive Web Application (PWA) designed to make building healthy habits fun and engaging. It combines real-time activity tracking, custom background alarms, mind games, and AI-simulated features to provide a complete wellness ecosystem.

**Developed with ❤️ Laxman Kuber & Team Junun**

---

## 🌟 Key Features

### 1. 🎮 Gamified Dashboard
* **Health Coins & Streaks:** Earn coins for completing daily habits and maintain streaks to level up.
* **Activity Analytics:** Interactive 7-day step bar charts and wellness radar charts powered by **Chart.js**.
* **Glassmorphism UI:** A sleek, futuristic, dark-themed UI with neon accents.

### 2. ⏰ Pro Background Alarm System (Lock-Screen Ready)
* **Service Worker Integration:** Uses `sw.js` to deliver high-priority push notifications even when the browser is minimized or the screen is locked.
* **Persistent Audio:** Bypasses browser autoplay policies using a custom "Audio Wake-Lock" technique, ensuring the alarm rings across tabs.
* **Actionable Notifications:** Mark habits as "Done" directly from the lock screen.

### 3. 📸 AI Food Scanner (Simulator)
* **Live Camera Feed:** Utilizes `MediaDevices API` to access the user's environment camera.
* **Dynamic Scanning Animation:** Simulates real-time AI scanning of meals.
* **Nutritional Analysis:** Provides a mock breakdown of calories, protein, and health scores to guide user diet.

### 4. 🧘‍♂️ Zen Meditation Mode
* **Guided Breathing:** A dynamic, visually soothing breathing circle (Inhale, Hold, Exhale).
* **Ambient Audio:** Integrated nature sounds for deep focus and relaxation.
* **Focus Timer:** Tracks meditation duration in real-time.

### 5. 🧠 Mind Games Hub
* **Reaction Focus Game:** A fast-paced target-clicking game to improve hand-eye coordination and reflexes.
* **Memory Match:** An emoji-based card matching game to boost short-term memory and cognitive function.

### 6. 🚶‍♂️ Live Sensor Tracking
* **Step Counter:** Uses the `DeviceMotion API` (accelerometer) to count physical steps in real-time.
* **Daily Challenges:** Automated rewards for hitting daily step goals (e.g., 5,000 steps).
* **GPS Tracking:** Real-time location detection using the `Geolocation API`.

### 7. 📝 Habit Management
* Add customizable daily habits with specific target times.
* Securely delete habits with AJAX (`fetch` API) without page reloads.

---

## 🛠️ Tech Stack

**Frontend:**
* HTML5 & CSS3 (Glassmorphism, Flexbox, CSS Animations)
* Vanilla JavaScript (ES6+)
* Chart.js (Data Visualization)
* Font Awesome v6.4.0 (Icons)

**Backend:**
* PHP 8.x (Secure routing, session management, and API endpoints)
* MySQL (Database for users, habits, and progress tracking)

**Advanced Web APIs Used:**
* Service Workers API (`sw.js`)
* Web Notifications API
* Web Audio API
* Navigator `MediaDevices` API (Camera)
* `DeviceMotionEvent` API (Step Tracking)
* Geolocation API

---

## ⚙️ Installation & Setup

1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/your-username/habitquest.git](https://github.com/your-username/habitquest.git)
