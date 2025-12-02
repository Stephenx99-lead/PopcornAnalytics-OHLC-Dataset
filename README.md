# PopcornAnalytics-OHLC-Dataset
High-quality crypto OHLC dataset reconstructed from raw trades (2013–2025). Free samples included.

---

## 📌 Overview

This repository contains multiple high-quality **XBTUSD 1-minute OHLC samples**, all reconstructed directly from raw Kraken trades using a custom pipeline.

This dataset is designed for:

- Algorithmic trading research  
- Backtesting engines  
- AI/ML modeling  
- Market microstructure analysis  
- Statistical validation  
- Candle reconstruction benchmarking  

Unlike typical exchange-provided candles, this dataset is **rebuilt entirely from raw trades**, ensuring:

✔ Zero intentional gaps  
✔ Millisecond-accurate timestamps  
✔ True trade-derived candles  
✔ Perfect 1-minute boundaries  
✔ Accurate base-currency volume  
✔ Long-range consistency (2013–2025)

---

# 📦 Free Sample Files

Free sample files included in this repository to validate structure and data quality.

---

## 🗓 1-Month Sample — November 2025 (Recent)
**File:** `xbtusd_1m_2025-11_sample.json.zip`  
**Candles:** 43,200  
**Range:** 2025-11-01 → 2025-11-30  

A full month of modern XBTUSD 1-minute candles, ideal for testing continuity, timestamps, and reconstruction quality.

---

## 🕰 20MB Historical Sample — 2013–2017
**File:** `xbtusd_1m_sample_20mb.zip`  
**Candles:** 349,376  
**Range:** 2013-10-06 → 2017-06-27  

A historical slice showing early Kraken BTC/USD trading behavior and long-term reconstruction consistency.

---

## 📅 20MB Recent Sample — 2025
**File:** `xbtusd_1m_sample_recent_20mb.zip`  
**Candles:** 361,005  
**Range:** 2025-03-24 → 2025-11-30  

A multi-month recent sample demonstrating modern liquidity and the output of the reconstruction pipeline.

---

# 📘 Column Definitions

Each 1-minute candle is stored in this format:

