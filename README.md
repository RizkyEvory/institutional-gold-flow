# Institutional Gold Flow Indicator

![XAUUSD](https://img.shields.io/badge/Symbol-XAUUSD%20%7C%20GOLD-gold)
![MT5](https://img.shields.io/badge/Platform-MetaTrader%205-blue)
![License](https://img.shields.io/badge/License-Free%20for%20personal%20use-green)
![Version](https://img.shields.io/badge/Version-1.00-brightgreen)

**Advanced non-repainting indicator for XAUUSD combining Volume Profile, COT data, and institutional confluence analysis.**

Designed for serious gold traders who want institutional-style edge without retail noise.

## Features

- **Dynamic Volume Profile**  
  - Point of Control (POC), High Volume Nodes (HVN), Value Area (70%)  
  - Adaptive bin size based on ATR  
  - Supports fixed period (default 20 days) or visible range

- **COT (Commitments of Traders) Integration**  
  - Net commercial positions with extreme detection  
  - Multiple sources: Manual, CSV file, or hardcoded (updated 2025)  
  - Reversal bias detection based on commercial extremes

- **Smart Confluence Engine (0-100%)**  
  - Price near HVN/POC  
  - COT extreme alignment  
  - Volume spike confirmation  
  - Strong rejection candle  
  - London/NY session filter

- **Non-Repainting Signals**  
  - Buy/Sell arrows only on closed bars  
  - High-probability reversal setups only

- **Professional Dashboard**  
  - Current market regime  
  - COT sentiment  
  - POC & Value Area levels  
  - Real-time confluence score  
  - Session status

- **Risk Management Visualization**  
  - ATR-based Stop Loss  
  - Multiple Take Profit levels (TP1 & TP2)  
  - Visual SL/TP lines on signal

- **Full Alert System**  
  - Popup, sound, push notification, email  
  - Signal logging to CSV

## Installation

1. Download `Institutional Gold Flow.mq5`
2. Place in your MT5 `MQL5/Indicators/` folder
3. Restart MetaTrader 5 or refresh Navigator
4. Drag indicator to XAUUSD chart (recommended H1 or H4)

## Optimal Settings

- Timeframe: H1 or H4
- Best performance during London/NY sessions
- Minimum confluence: 70-80%
- Update COT data weekly (Tuesday after CFTC release)

## COT Data Update

The indicator includes:
- Hardcoded data (2025)
- CSV import support
- Manual input option

For latest COT data:
- Download from CFTC.gov (Legacy Report - Futures Only)
- Save as `cot_gold_data.csv` in `MQL5/Files/`
- Set `InpCOT_DataSource = 1`

## Screenshots

*(Add your own screenshots here after testing)*
- Dashboard view
- Signal example with SL/TP
- Volume Profile levels

## Author

© M4DI~UciH4  
GitHub: https://github.com/RizkyEvory

> This indicator is provided for educational and personal use. No trading guarantees. Use proper risk management.

---

⭐ Star this repo if you find it useful!  
💬 Issues and suggestions welcome!
