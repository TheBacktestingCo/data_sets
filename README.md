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
- **Institutional Coverage**: High-frequency datasets for major liquid assets.

---

## 📂 Repository Structure

The data is organized into root-level directories for maximum accessibility.

```bash
data_sets/
├── csv/         # Standard CSV files for quick analysis
└── parquet/     # High-performance Parquet files for big data workflows
```

### 📊 Master Data Sets (1m Interval)

| Asset       | Format        | Start Time          | End Time            |
| :---------- | :------------ | :------------------ | :------------------ |
| **BTCUSDT** | CSV & Parquet | 2022-01-01 00:00:00 | 2026-01-31 23:59:00 |
| **ETHUSDT** | CSV & Parquet | 2022-01-01 00:00:00 | 2026-01-31 23:59:00 |
| **SOLUSDT** | CSV & Parquet | 2022-01-01 00:00:00 | 2026-01-31 23:59:00 |
| **XRPUSDT** | CSV & Parquet | 2022-01-01 00:00:00 | 2026-01-31 23:59:00 |

---

## 🚀 Getting Started

### 1. Fast Loading with Python (Pandas + PyArrow)
For large-scale backtesting, we recommend using the `.parquet` files for significantly faster I/O.

```python
import pandas as pd

# Load ETH 1m data in seconds
df = pd.read_parquet('parquet/ETHUSDT_1m_5yr.parquet')
print(df.head())
```

### 2. Direct Download
You can download files directly from the repository or clone it for full access:
```bash
git clone https://github.com/TheBacktestingCo/data_sets.git
```

---

## 🎯 SEO & Keywords
`algorithmic trading` `backtesting data` `crypto historical data` `ohlcv` `1m crypto data` `quant finance` `machine learning for trading` `historical market data` `python trading` `pandas` `parquet data`

---

## 🤝 Contributing
Found a gap? Have more data to share? Contributions are welcome! 
1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AddMoreData`)
3. Commit your Changes (`git commit -m 'Add new asset data'`)
4. Push to the Branch (`git push origin feature/AddMoreData`)
5. Open a Pull Request

---

## 📜 License
Distributed under the MIT License. See `LICENSE` for more information.

---

**Developed with ❤️ by [TheBacktestingCo](https://github.com/TheBacktestingCo)**
*Empowering traders with institutional-grade data.*


---

## 📈 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TheBacktestingCo/data_sets&type=Date)](https://star-history.com/#TheBacktestingCo/data_sets&Date)
