# PopcornAnalytics-OHLC-Dataset
High-quality crypto OHLC dataset reconstructed from raw Kraken trades (2013–2025). Free samples included.

---

## 📌 Overview

This repository contains multiple **XBTUSD 1-minute OHLC samples** reconstructed directly from raw Kraken trade data.  
The candles are rebuilt using a custom pipeline that ensures:

- Zero intentional gaps  
- Millisecond-accurate timestamps  
- True trade-derived OHLC  
- Proper 1-minute boundaries  
- Accurate base-currency volume  
- Long-term consistency (2013 → 2025)

These samples help traders and researchers validate accuracy before purchasing the full dataset.

---

# 📦 Free Sample Files

## 🗓 1-Month Sample — November 2025
**File:** `xbtusd_1m_2025-11_sample.json.zip`  
**Candles:** 43,200  
**Range:** 2025-11-01 → 2025-11-30  

A full month of recent XBTUSD data showing modern liquidity and precise reconstruction.

---

## 🕰 Historical Sample (2013–2017) — 20MB
**File:** `xbtusd_1m_sample_20mb.zip`  
**Candles:** 349,376  
**Range:** 2013-10-06 → 2017-06-27  

A look into Kraken’s early market history.

---

## 📅 Recent Sample (2025) — 20MB
**File:** `xbtusd_1m_sample_recent_20mb.zip`  
**Candles:** 361,005  
**Range:** 2025-03-24 → 2025-11-30  

A larger sample demonstrating multi-month reconstruction continuity.

---

# 📘 Column Definitions

Each 1-minute candle follows the structure:

