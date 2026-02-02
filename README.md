# 🚀 High-Frequency Crypto Data Sets for Algorithmic Trading & Backtesting

[![GitHub stars](https://img.shields.io/github/stars/TheBacktestingCo/data_sets.svg?style=social&label=Star&maxAge=2592000)](https://github.com/TheBacktestingCo/data_sets/stargazers/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Market: Crypto](https://img.shields.io/badge/Market-Crypto-blueviolet.svg)](https://www.binance.com)
[![Format: Parquet/CSV](https://img.shields.io/badge/Format-Parquet%20%7C%20CSV-blue.svg)](#data-formats)

The ultimate open-source repository for **high-fidelity cryptocurrency market data**. Engineered specifically for quant traders, data scientists, and algorithmic developers who require clean, ready-to-use historical data for **backtesting**, **strategy optimization**, and **machine learning** model training.

---

## 💎 Why This Repository?

Accessing high-quality historical data is often the biggest bottleneck in quantitative finance. This repository provides:

- **1-Minute Granularity**: Master-level precision for intra-day strategy development.
- **Multiple Formats**: Optimized **Apache Parquet** for speed and standard **CSV** for compatibility.
- **Clean Data**: Pre-processed to handle gaps, outliers, and formatting inconsistencies.
- **Diverse Assets**: Covering major pairs like BTC, ETH, XRP and trending tokens like HYPE, TRUMP.

---

## 📂 Repository Structure

The data is organized by exchange and format to ensure seamless integration into your trading pipeline.

```bash
data_sets/
└── binance/
    ├── csv/         # Standard CSV files for quick analysis
    └── parquet/     # High-performance Parquet files for big data workflows
```

### 📊 Available Data Sets (Binance 1m)

| Symbol | Parquet | CSV | Timeframe |
| :--- | :---: | :---: | :---: |
| **BTC/USDT** | ✅ | ⌛ | 1m |
| **ETH/USDT** | ✅ | ✅ | 1m |
| **XRP/USDT** | ✅ | ⌛ | 1m |
| **HYPE/USDT** | ✅ | ⌛ | 1m |
| **TRUMP/USDT** | ✅ | ⌛ | 1m |
| **ALGO/USDT** | ✅ | ⌛ | 1m |
| **ZEC/USDT** | ✅ | ⌛ | 1m |

---

## 🚀 Getting Started

### 1. Fast Loading with Python (Pandas + PyArrow)
For large-scale backtesting, we recommend using the `.parquet` files for significantly faster I/O.

```python
import pandas as pd

# Load ETH 1m data in seconds
df = pd.read_parquet('binance/parquet/ETHUSDT_1m_master.parquet')
print(df.head())
```

### 2. Direct Download
You can download files directly from the `binance/` directory or clone the repository for full access:
```bash
git clone https://github.com/TheBacktestingCo/data_sets.git
```

---

## 🎯 SEO & Keywords
`algorithmic trading` `backtesting data` `crypto historical data` `binance ohlcv` `1m crypto data` `quant finance` `machine learning for trading` `historical market data` `python trading` `pandas` `parquet data`

---

## 🤝 Contributing
Found a gap? Have more data to share? Contributions are welcome! 
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AddMoreData`)
3. Commit your Changes (`git commit -m 'Add SOLUSDT 1m data'`)
4. Push to the Branch (`git push origin feature/AddMoreData`)
5. Open a Pull Request

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

---

**Developed with ❤️ by [TheBacktestingCo](https://github.com/TheBacktestingCo)**
*Empowering traders with institutional-grade data.*
