# Agricultural Commodity Price Dashboard (2026)

An interactive **Microsoft Power BI** dashboard for exploring agricultural commodity prices across Indian markets. The report brings together market-level and commodity-level views to help users compare prices and examine differences across states, dates, commodities, and grades.

## Dashboard Preview

### Agricultural Market Overview

![Agricultural Market Overview dashboard page](<images/Screenshot 2026-11-18 120423.png>)

### Commodity Price Analysis

![Commodity Price Analysis dashboard page](<images/Screenshot 2026-11-18 120532.png>)

## Dashboard Video

<video controls width="100%">
  <source src="videos/Agricultural_commodity_dashboard.mp4" type="video/mp4">
  Your browser does not support embedded video. [Open or download the video](<videos/Agricultural_commodity_dashboard.mp4>).
</video>

[Open or download the dashboard video](<videos/Agricultural_commodity_dashboard.mp4>)

## Dashboard Pages

### 1. Agricultural Market Overview

The overview page presents high-level market information and price patterns, including:

- Average modal price
- Minimum and maximum price indicators
- Total commodities and total markets
- Average modal price by state
- Average modal price by commodity
- Monthly average modal price
- Average modal price over arrival dates
- Commodity distribution
- Year and state filters

### 2. Commodity Price Analysis

The analysis page provides a more detailed comparison of commodity performance, including:

- Commodity-level average modal price comparisons
- Average price range by commodity
- Commodity distribution and counts
- Commodity and year filters
- Grade-wise commodity analysis
- Minimum, maximum, and average price summaries
- Market-level information

## Key Measures and Fields

The report uses fields and measures from the `Indian Agricultural datset` model, including:

| Measure / Field | Purpose |
|---|---|
| Average Modal Price | Compares average modal prices across selected categories |
| Minimum Price | Shows the minimum price in the selected context |
| Maximum Price | Shows the maximum price in the selected context |
| Average Price Range | Supports comparison of price ranges |
| Total Commodities | Summarises the commodity count |
| Total Markets | Summarises the market count |
| State | Enables state-level analysis |
| Commodity | Enables commodity-level analysis |
| Year / Arrival Date / Month | Supports time-based filtering and trends |
| Grade | Supports grade-wise comparison |

All visuals respond to the report's available slicers and filter selections.

## Tools Used

- **Microsoft Power BI Desktop** — report development and interactive visualisation
- **Power Query** — data preparation and transformation within Power BI
- **DAX** — measures and aggregations used in the report

## Repository Contents

```text
Agricultural-Commodity-Price-Dashboard/
│
├── agricultural commodity price 2026.pbix
├── README.md
├── images/
    ├── Screenshot 2026-11-18 120423.png
    └── Screenshot 2026-11-18 120532.png
└── videos/
    └── Agricultural_commodity_dashboard.mp4
```

## How to Use

1. Download or clone this repository.
2. Open `agricultural commodity price 2026.pbix` using **Microsoft Power BI Desktop**.
3. Explore the report pages: **Agricultural Market Overview** and **Commodity Price Analysis**.
4. Use the year, state, and commodity slicers to filter the visuals.
5. Select chart elements to cross-filter other visuals where supported.

If Power BI asks for data-source credentials or cannot refresh the report, check the data-source settings in **Transform data → Data source settings**. The report can only be refreshed if the original data source is available and accessible.

## Notes

- This repository contains the Power BI report (`.pbix`).
- The exact dataset source, licence, coverage period, and refresh frequency should be documented here once confirmed.
- Price values and comparisons depend on the data loaded into the report and the active filters.
- This dashboard is intended for data exploration and analysis; it should not be treated as an official price quotation or trading recommendation.

## Future Improvements

- Add a data-source description, dataset link, and licence.
- Include a data dictionary and definitions for calculated measures.
- Document the dataset's date coverage and refresh process.

## Author

**Manish Purohit**

If you find this project useful, feel free to star the repository.
