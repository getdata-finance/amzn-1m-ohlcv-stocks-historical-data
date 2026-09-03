# AMZN 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-637_283_rows-blue)](https://getdata.finance/datasets/amzn) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/amzn)

### -> [**Download the full AMZN dataset on getdata.finance**](https://getdata.finance/datasets/amzn)

**AMZN 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Amazon**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Amazon** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/amzn) · **637,283** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `AMZN_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/amzn)** — **637,283** `1m` rows, **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[AMZN_1m.csv](https://github.com/getdata-finance/amzn-1m-ohlcv-stocks-historical-data/blob/main/AMZN_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/amzn-1m-ohlcv-stocks-historical-data/main/AMZN_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/amzn))** |
|---|--:|---|
| Instrument | Amazon · US stocks | Amazon · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **637,283** |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `AMZN_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/amzn) |
| Coverage report | — | [AMZN coverage](https://getdata.finance/coverage/amzn) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/amzn)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`AMZN_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T20:00:00+00:00 | 208.7 | 208.81 | 208.6 | 208.61 | 201 |
| 2026-02-06T20:01:00+00:00 | 208.61 | 208.78 | 208.61 | 208.66 | 125 |
| 2026-02-06T20:02:00+00:00 | 208.66 | 208.68 | 208.41 | 208.42 | 118 |
| 2026-02-06T20:03:00+00:00 | 208.42 | 208.74 | 208.41 | 208.7 | 186 |
| 2026-02-06T20:04:00+00:00 | 208.7 | 208.79 | 208.45 | 208.71 | 189 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 253.72 | 254.37 | 253.72 | 254.18 | 164 |
| 2026-09-01T19:56:00+00:00 | 254.18 | 254.2 | 254.06 | 254.11 | 147 |
| 2026-09-01T19:57:00+00:00 | 254.11 | 254.18 | 254.04 | 254.12 | 147 |
| 2026-09-01T19:58:00+00:00 | 254.12 | 254.25 | 254.01 | 254.25 | 119 |
| 2026-09-01T19:59:00+00:00 | 254.25 | 254.51 | 254.05 | 254.48 | 307 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full AMZN archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full AMZN dataset on getdata.finance](https://getdata.finance/datasets/amzn)**
