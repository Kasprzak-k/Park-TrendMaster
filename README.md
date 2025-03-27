# PARK TrendMaster Pro

<img src="https://img.shields.io/badge/Version-3.0-blue" alt="Version">
<img src="https://img.shields.io/badge/PineScript-v6-green" alt="PineScript">

Advanced trend analysis indicator with smart adaptive profiles.

## ✨ Key Features
- **3 Trading Profiles**  
  `Aggressive` | `Default` | `Conservative`  
  Auto-adjusts MA/RSI parameters

- **Smart Time Filter**  
  Signals only at user-defined intervals (15/30/60min)

- **Professional Tools**  
  - Dynamic Support/Resistance  
  - Volume Zones  
  - Gap Detection (10+ pts)  

## 📜 Changelog
v3.0 (Current)

✅ Adaptive trading profiles

✅ Time-based signal filtering

✅ Enhanced info panel

## 🛠 Integrated Professional Tools

Dynamic Support/Resistance (50 periods)

High Volume Zones (1.5x above average)

Gap Detection (minimum 10 points)

Real-time data dashboard

##  Installation
1. Open TradingView
2. Copy/Paste script
3. Configure:
```pinescript
// Customize in UI:
signalConfig = input.string('Default', 'Trading Profile')
signalTimeframe = input(30, 'Signal Window (mins)')
