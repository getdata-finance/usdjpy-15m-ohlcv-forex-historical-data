# USDJPY 15m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-615_732_rows-blue)](https://getdata.finance/datasets/usdjpy) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usdjpy)

### -> [**Download the full USDJPY dataset on getdata.finance**](https://getdata.finance/datasets/usdjpy)

**USDJPY 15m OHLCV forex historical data** — ultra high-quality 15m OHLCV for **US Dollar / Japanese Yen**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **US Dollar / Japanese Yen** (Forex)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usdjpy) · **615,732** `15m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `USDJPY_15m.csv` (3,700 rows, `2026-07-09` -> `2026-09-02`, 360.36 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usdjpy)** — **615,732** `15m` rows (full `1m`: 9,209,554), **11 timeframes**, `2001-11-28` -> `2026-09-02`.

## Download sample

**[USDJPY_15m.csv](https://github.com/getdata-finance/usdjpy-15m-ohlcv-forex-historical-data/blob/main/USDJPY_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usdjpy-15m-ohlcv-forex-historical-data/main/USDJPY_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/usdjpy-15m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usdjpy-15m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/usdjpy-15m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usdjpy](https://getdata.finance/datasets/usdjpy)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usdjpy))** |
|---|--:|---|
| Instrument | US Dollar / Japanese Yen · Forex | US Dollar / Japanese Yen · Forex |
| Timeframes | `15m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 15m rows | 3,700 | **615,732** |
| Size | 360.36 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Period | `2026-07-09` -> `2026-09-02` | `2001-11-28` -> `2026-09-02` |
| File | `USDJPY_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usdjpy) |
| Coverage report | — | [USDJPY coverage](https://getdata.finance/coverage/usdjpy) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usdjpy)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/usdjpy) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USDJPY_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-09T13:15:00+00:00 | 163.024 | 163.025 | 162.903 | 162.984 | 2977 |
| 2026-07-09T13:30:00+00:00 | 162.984 | 162.987 | 162.918 | 162.94 | 2331 |
| 2026-07-09T13:45:00+00:00 | 162.94 | 162.978 | 162.924 | 162.949 | 1477 |
| 2026-07-09T14:00:00+00:00 | 162.949 | 163.002 | 162.895 | 162.991 | 2736 |
| 2026-07-09T14:15:00+00:00 | 162.991 | 163.01 | 162.966 | 162.988 | 1670 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-02T01:00:00+00:00 | 160.289 | 160.321 | 160.28 | 160.289 | 2593 |
| 2026-09-02T01:15:00+00:00 | 160.289 | 160.304 | 160.268 | 160.281 | 2418 |
| 2026-09-02T01:30:00+00:00 | 160.281 | 160.346 | 160.275 | 160.343 | 2516 |
| 2026-09-02T01:45:00+00:00 | 160.343 | 160.392 | 160.343 | 160.368 | 1706 |
| 2026-09-02T02:00:00+00:00 | 160.368 | 160.379 | 160.368 | 160.378 | 56 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('USDJPY_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USDJPY_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('USDJPY_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='15min')
print(pf.stats())
```

## Download full data

The complete **USDJPY** archive on **[getdata.finance](https://getdata.finance/datasets/usdjpy)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **615,732** rows at `15m`, plus all other timeframes in the same ZIP.

**[-> Get the full USDJPY dataset on getdata.finance](https://getdata.finance/datasets/usdjpy)**

---
*GetData · USDJPY 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usdjpy)*
