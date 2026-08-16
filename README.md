# Multi-Channel Ad Performance Analytics (Excel)

Excel-based analysis of Facebook Ads and Google Ads campaign performance, covering **Oct 2019 – Jul 2020**. Built to practice data cleaning, PivotTables, and dashboard design on a real multi-channel marketing dataset.

## 📊 What's inside

| Sheet | Description |
|---|---|
| `Data` | Cleaned master dataset (16,834 rows × 16 columns) — one row per campaign/audience/device/age combination |
| `Dashboard` | Summary dashboard with 8 charts (spend trends, platform split, device/age breakdown) |
| `Pivot Table` | Spend, CPC, and CPA summarized by platform and age group |
| `Device_by_Age` | Performance broken down by device type × age bracket |
| `Subchannels` | Subchannel-level detail (Brand / Competitor / Generic for Google Ads; Facebook Ads channel) |
| `Ayrıntı1–4` | Raw/staging detail exports feeding the pivots and dashboard |

## 🧩 Key fields

`Date`, `product`, `phase`, `campaign_platform`, `campaign_type`, `communication_medium`, `subchannel`, `audience_type`, `creative_type`, `creative_name`, `device`, `age`, `spends`, `impressions`, `clicks`, `link_clicks`

## 🔍 Dimensions covered

- **Platforms:** Google Ads, Facebook Ads
- **Campaign types:** Search, Conversions
- **Subchannels:** Brand, Competitor, Generic, Facebook Ads
- **Devices:** Desktop, Mobile, Tablet
- **Age groups:** 18–24, 25–34, 35–44, 45–54, 55–64, 65+, Undetermined

## 🛠 Skills demonstrated

- Data cleaning and structuring of raw ad-platform exports
- PivotTables and pivot charts
- Multi-dimensional performance analysis (platform × device × age × subchannel)
- Dashboard design with linked charts (line, bar, pie)
- CPC / CPA calculation and comparison across channels

## ⚠️ Note on data quality

A small number of rows in the `spends` column contain extreme outlier values inconsistent with the rest of the dataset. These were left in the raw sheets for transparency but should be filtered out before drawing conclusions from aggregate spend totals.

## 📥 How to use

1. Download `AD_ADVERTISEMENT.xlsx`.
2. Open in Excel (or LibreOffice Calc — some pivot chart formatting may render slightly differently).
3. Start on the `Dashboard` sheet for the high-level view, then drill into `Data`, `Pivot Table`, `Device_by_Age`, or `Subchannels` for detail.
