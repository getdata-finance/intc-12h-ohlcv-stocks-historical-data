# INTC 12h OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-3_131_rows-blue)](https://getdata.finance/datasets/intc) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/intc)

### -> [**Download the full INTC dataset on getdata.finance**](https://getdata.finance/datasets/intc)

**INTC 12h OHLCV stocks historical data** — ultra high-quality 12h OHLCV for **Intel**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 12h OHLCV** for **Intel** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`12h`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/intc) · **3,131** `12h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `12h` sample updated in sync

> **Sample on GitHub** · `INTC_12h.csv` (127 rows, `2026-03-23` -> `2026-09-22`, 12.66 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/intc)** — **3,131** `12h` rows (full `1m`: 634,759), **11 timeframes**, `2011-05-09` -> `2026-09-22`.

## Download sample

**[INTC_12h.csv](https://github.com/getdata-finance/intc-12h-ohlcv-stocks-historical-data/blob/main/INTC_12h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/intc-12h-ohlcv-stocks-historical-data/main/INTC_12h.csv)) · [GitHub Releases](https://github.com/getdata-finance/intc-12h-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/intc-12h-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/intc-12h-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/intc](https://getdata.finance/datasets/intc)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/intc))** |
|---|--:|---|
| Instrument | Intel · US stocks | Intel · US stocks |
| Timeframes | `12h` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 12h rows | 127 | **3,131** |
| Size | 12.66 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Period | `2026-03-23` -> `2026-09-22` | `2011-05-09` -> `2026-09-22` |
| File | `INTC_12h.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Coverage report | — | [INTC coverage](https://getdata.finance/coverage/intc) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`12h` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/intc)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `12h` sample · [getdata.finance](https://getdata.finance/datasets/intc) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `12h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`INTC_12h.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-23T12:00:00+00:00 | 43.43 | 45.01 | 43.28 | 43.54 | 65844 |
| 2026-03-24T12:00:00+00:00 | 43.54 | 43.86 | 42.72 | 43.64 | 59783 |
| 2026-03-25T12:00:00+00:00 | 43.64 | 47.39 | 43.64 | 46.73 | 59344 |
| 2026-03-26T12:00:00+00:00 | 46.73 | 46.73 | 43.46 | 43.65 | 50554 |
| 2026-03-27T12:00:00+00:00 | 43.65 | 43.67 | 42.4 | 42.68 | 50844.90966 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-16T12:00:00+00:00 | 97.04 | 104.34 | 97.04 | 100.93 | 103977 |
| 2026-09-17T12:00:00+00:00 | 100.93 | 111.31 | 100.93 | 108.8 | 84789 |
| 2026-09-18T12:00:00+00:00 | 108.8 | 110.38 | 106.31 | 108.61 | 66698 |
| 2026-09-21T12:00:00+00:00 | 108.61 | 124.66 | 108.61 | 121.8 | 106209 |
| 2026-09-22T12:00:00+00:00 | 121.8 | 124.03 | 120.02 | 123.78 | 83406 |

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

df = pd.read_csv('INTC_12h.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('INTC_12h.csv', parse_dates=['datetime'])
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

df = pd.read_csv('INTC_12h.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='12h')
print(pf.stats())
```

## Download full data

The complete **INTC** archive on **[getdata.finance](https://getdata.finance/datasets/intc)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **3,131** rows at `12h`, plus all other timeframes in the same ZIP.

**[-> Get the full INTC dataset on getdata.finance](https://getdata.finance/datasets/intc)**

---
*GetData · INTC 12h OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/intc)*
