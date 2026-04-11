# 🏏 Auction Orbit – Live Auction System

[![Real-time](https://img.shields.io/badge/Real--time-Firebase-orange?style=flat-square&logo=firebase)](https://firebase.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg?style=flat-square)](https://github.com/Akshitpatel1115/Auction-Orbit/graphs/commit-activity)

**Auction Orbit** is a premium, real-time auction management system designed for cricket leagues and professional bidding events. It provides a seamless, high-stakes experience with instant synchronization across all devices.

---

## 🌟 Key Features

- **🚀 Real-Time Sync:** Instant updates of bids, player status, and team purses using Firebase Realtime Database.
- **🎙️ Automated Voice Announcements:** High-quality voice alerts for new players, current bids, and "SOLD" results.
- **🛡️ Robust Admin Panel:** Centralized control for the auctioneer to manage bidding, shuffle players, and finalize sales.
- **💰 Smart Purse Management:** Automated budget tracking for teams with built-in validation to prevent over-bidding.
- **📋 Live Dashboards:** Beautifully designed screens for the public, including live auction stats, player cards, and team rosters.
- **📱 Responsive Design:** Premium, dark-mode UI optimized for large event screens, tablets, and mobile devices.

---

## 🛠️ Technology Stack

- **Frontend:** HTML5, CSS3 (Vanilla), JavaScript (ES6+)
- **Backend:** [Firebase Realtime Database](https://firebase.google.com/)
- **Hosting:** [Firebase Hosting](https://firebase.google.com/docs/hosting)
- **Icons & Fonts:** FontAwesome 6, Google Fonts (Manrope, Inter, Poppins)

---

## 🚀 Getting Started

### Prerequisites
- A **Google Account** (for Firebase setup).
- [Node.js](https://nodejs.org/) installed on your machine.
- [Firebase CLI](https://firebase.google.com/docs/cli) installed:
  ```bash
  npm install -g firebase-tools
  ```

### Local Setup
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Akshitpatel1115/Auction-Orbit.git
   cd Auction-Orbit
   ```
2. **Firebase Configuration:**
   Update the `firebaseConfig` object in `index.html` and `admin.html` with your own Firebase project credentials.

3. **Deploy to Live:**
   ```bash
   firebase login
   firebase init
   firebase deploy
   ```

---

## 📂 Project Structure

```text
├── admin.html          # Admin control dashboard
├── index.html          # Main live auction screen
├── login.html          # Secure admin login page
├── all_players.html    # Player database view
├── all_teams.html      # Team rosters and purse overview
├── style.css           # Core styling and design system
├── players.json        # Initial player data source
├── teams.json          # Initial team data source
└── firebase.json       # Firebase hosting configuration
```

---

## 👤 Author

**Akshit Patel**
- GitHub: [@Akshitpatel1115](https://github.com/Akshitpatel1115)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*Made with ❤️ for the cricket community.*
