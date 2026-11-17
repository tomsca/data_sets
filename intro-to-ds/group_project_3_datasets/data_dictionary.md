# Data dictionary

The readings are stored in two files. This dictionary names the columns in the four files.

| File | Column | What it holds |
|:-----|:-------|:--------------|
| `readings_a.csv`, `readings_b.csv` | `RecordID` | Unique record identifier |
| `readings_a.csv`, `readings_b.csv` | `GeoJoinID` | Geography code |
| `readings_a.csv`, `readings_b.csv` | `GeoType` | Geography type |
| `readings_a.csv`, `readings_b.csv` | `IndicatorID` | Indicator id |
| `readings_a.csv`, `readings_b.csv` | `IndicatorMeasure` | Indicator and measure, separated by ` :: ` |
| `readings_a.csv`, `readings_b.csv` | `TimePeriod` | Time period |
| `readings_a.csv`, `readings_b.csv` | `DataValue` | Data value |
| `places.csv` | `GeoJoinID` | Geography code |
| `places.csv` | `GeoType` | Geography type |
| `places.csv` | `PlaceName` | Name of the geographic area |
| `measures.csv` | `IndicatorID` | Indicator id |
| `measures.csv` | `IndicatorName` | Name of the indicator |
| `measures.csv` | `Units` | Unit of the indicator |

Fine particles are in micrograms per cubic meter. Nitrogen dioxide is in parts per billion.
