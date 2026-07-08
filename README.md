# AUS200 15m OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-4_633_407_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### -> [**Download the full AUS200 dataset on ork.ad**](https://ork.ad/)

**AUS200 15m OHLCV stock index historical data** — ultra high-quality 15m OHLCV for **Australia 200**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **Australia 200** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **4,633,407** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AUS200_15m.csv` (10,561 rows, `2026-01-04` -> `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **4,633,407** `1m` rows (~217.63 MB), **13 timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`), `2008-09-10` -> `2026-07-03`.

## Download sample

**[AUS200_15m.csv](https://github.com/ork-ad/aus200-15m-ohlcv-index-historical-data/blob/main/AUS200_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/aus200-15m-ohlcv-index-historical-data/main/AUS200_15m.csv)) · [GitHub Releases](https://github.com/ork-ad/aus200-15m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/aus200-15m-ohlcv-index-historical-data/](https://ork-ad.github.io/aus200-15m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Australia 200 · Stock index | Australia 200 · Stock index |
| Timeframes | `15m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 1m rows | 10,561 | **4,633,407** |
| Size | 0.59 MB | ~217.63 MB |
| Period | `2026-01-04` -> `2026-07-03` | `2008-09-10` -> `2026-07-03` |
| File | `AUS200_15m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`15m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `15m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_15m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T22:45:00Z | 8737.5 | 8737.5 | 8715.12 | 8728.84 | 98 |
| 2026-01-04T23:00:00Z | 8728.84 | 8747.24 | 8726.72 | 8738.24 | 457 |
| 2026-01-04T23:15:00Z | 8738.24 | 8752.73 | 8738.22 | 8749.72 | 370 |
| 2026-01-04T23:30:00Z | 8749.72 | 8759.25 | 8741.72 | 8741.73 | 375 |
| 2026-01-04T23:45:00Z | 8741.73 | 8743.74 | 8733.23 | 8737.24 | 414 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-03T19:30:00Z | 8814.72 | 8817.23 | 8814.72 | 8816.24 | 17 |
| 2026-07-03T19:45:00Z | 8816.24 | 8816.24 | 8811.72 | 8811.72 | 31 |
| 2026-07-03T20:00:00Z | 8811.72 | 8811.74 | 8808.71 | 8808.71 | 6 |
| 2026-07-03T20:15:00Z | 8808.71 | 8808.73 | 8805.22 | 8807.73 | 15 |
| 2026-07-03T20:30:00Z | 8807.73 | 8810.23 | 8807.73 | 8808.73 | 7 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUS200_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_15m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('AUS200_15m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **4,633,407** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on ork.ad](https://ork.ad/)**

---
*GetData · AUS200 15m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-08 UTC*
