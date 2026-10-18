# Full House: AFL attendance trends

FIT3179 Data Visualisation 2 · Topic 10: Sports Attendance Trends


## Files
```
index.html     Website Vis
style.css      layout grid, typography, colours
specs/         Vega-Lite JSON files for charts
data/          data
```

## Charts
| # | File | Idiom | Advanced? |
|---|------|-------|-----------|
| 1 | `01_season_trend.vl.json` | Annotated line + area chart |
| 2 | `02_cross_code_waffle.vl.json` | Unit (waffle) chart |
| 3 | `03_map_city_symbols.vl.json` | **Map:** proportional symbol map |
| 4 | `04_map_choropleth.vl.json` | **Map:** choropleth (log scale, per capita) |
| 5 | `05_map_venue_spikes.vl.json` | **Map:** spike map |
| 6 | `06_map_tile_grid.vl.json` | **Map:** tile-grid cartogram with diverging colour + radio buttons |
| 7 | `07_club_season_heatmap.vl.json` | Heatmap (club × season) |
| 8 | `08_club_rank_bump.vl.json` | Bump chart (rank over time, click to highlight) |
| 9 | `09_members_vs_crowds.vl.json` | Connected scatterplot |
| 10 | `10_day_time_heatmap.vl.json` | Heatmap (day × start time) |
| 11 | `11_slot_density.vl.json` | Density plot (click legend to filter) |
| 12 | `12_club_draw_boxplot.vl.json` | Box plot with every game overlaid |



## Data sources
- AFL Tables: season attendance summary 1990–2026, and the 2026 season page (match crowds, rounds 1–15)
- footyinfo: attendance by season (cross-check)
- Wikipedia: 2023, 2024 and 2025 AFL season pages (club attendance and membership tables)
- austadiums.com: AFL crowds by stadium (2025), plus NRL, A-League and BBL season crowds
- Australian Bureau of Statistics: state population, September 2025
- rowanhogan/australian-states: state boundary GeoJSON (simplified with mapshaper)
