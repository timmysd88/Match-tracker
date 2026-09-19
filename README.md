# ⚽ Football Stat Tracker

A lightweight, mobile-first web application designed for touchline football (soccer) match tracking. Built for coaches and parents to easily record real-time player statistics and match impact without missing the action on the pitch.

## ✨ Key Features

*   📱 **Mobile-Optimized Interface:** Features large, tap-friendly +/- buttons designed for quick, one-handed use while standing on the touchline.
*   🔄 **Smart Position Switching:** The interface dynamically adapts based on the selected player. Outfield players show metrics like passing, tackles, and crossing, while Goalkeepers get a tailored interface for saves, distribution, and area command.
*   💾 **Auto-Save & Persistent Storage:** Built using browser `localStorage`. If your phone screen locks, you accidentally close the tab, or the browser refreshes, zero data is lost. Your stats remain exactly where you left them.
*   📊 **One-Tap CSV Export:** Instantly compile the entire team's match data into a neatly formatted `.csv` file. It downloads directly to your device and is pre-formatted to open perfectly in Excel, Google Sheets, or OpenOffice.
*   👥 **Dynamic Roster Management:** Add players on the fly with their name, shirt number, and specific position. Switch between players instantly during the match.

## 🚀 How to Use (Live App)

Because this is a Single Page Application (SPA) built with vanilla HTML/JS, it runs directly in your web browser. 

1. **Open the live tracker here:** `https://timmysd88.github.io/football-stat-tracker/` 
2. **Add to Home Screen:** For the best experience, open the link in Safari (iOS) or Chrome (Android), open the browser menu, and select **"Add to Home Screen"**. This will install the tracker as a full-screen app icon on your phone.
3. **Start Tracking:** Tap the top banner to build your matchday roster. Select a player to start tracking their stats.
4. **Export:** At the full-time whistle, tap **Export** to download the team's spreadsheet. 
5. **Reset:** Use the reset button in the player menu to wipe the slate clean for the next fixture.

## 🔒 Data Privacy

This application is 100% client-side. No data is sent to a server, database, or back to GitHub. All player names, numbers, and statistics are stored locally on the specific physical device running the app. 

## 🛠️ Built With
*   HTML5
*   CSS3
*   Vanilla JavaScript (ES5/ES6)
