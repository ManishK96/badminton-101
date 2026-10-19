# 🏸 Badminton 101 - Tracker, Head-to-Head & Monthly Champion Adjudicator

A real-time badminton match tracker designed for friends to track scores, view head-to-head records, calculate monthly standings, and adjudge monthly champions.

## 🚀 Live Hosting on GitHub Pages (3 Clicks)

1. Create a new repository on your GitHub account (e.g. `badminton-101`).
2. Upload the contents of this folder (`index.html`, `README.md`, etc.) to the `main` branch.
3. In your GitHub repository, go to **Settings → Pages**.
4. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
5. Your app will be live at: `https://<your-github-username>.github.io/badminton-101/`!

---

## ☁️ Free Real-Time Syncing (Firebase)

The app works offline with local storage, but also includes built-in Google Firebase Realtime Database syncing so all players can log games from their own phones in real time:

1. Go to [Firebase Console](https://console.firebase.google.com/) and click **Add project** (100% free Spark plan).
2. In the left sidebar, click **Build → Realtime Database**, then click **Create Database** (choose US or closest region).
3. Choose **Start in test mode** so your group can read and write scores.
4. Go to **Project Settings (⚙️) → General**, scroll to **Your apps**, click the **Web (</>)** icon, and copy the `firebaseConfig` snippet.
5. In your live Badminton app, tap **`(...)` → Firebase Real-time Sync** (or click the **Local Mode** badge at the top) and paste the config snippet.
6. The badge will switch to **🟢 Live Synced**! Any match logged on any phone will immediately show up on everyone's screen.
