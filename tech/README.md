# Teknik (Technology)

11 datasets — 2,232 records

> Browse at [listbase.org/sv/tech/](https://listbase.org/sv/tech/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Emoji – namn på svenska (CLDR)](sv-emoji-namn.json) | 1,966 | 280 KB | [CSV](sv-emoji-namn_SV.csv) | [Excel](sv-emoji-namn_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-emoji-namn/) |
| [Världens tidszoner (IANA / CLDR på svenska)](sv-tidszoner.json) | 133 | 23 KB | [CSV](sv-tidszoner_SV.csv) | [Excel](sv-tidszoner_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner/) |
| [Tidszoner – America (46)](sv-tidszoner-america.json) | 46 | 9 KB | [CSV](sv-tidszoner-america_SV.csv) | [Excel](sv-tidszoner-america_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-america/) |
| [Tidszoner – Asia (27)](sv-tidszoner-asia.json) | 27 | 6 KB | [CSV](sv-tidszoner-asia_SV.csv) | [Excel](sv-tidszoner-asia_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-asia/) |
| [Tidszoner – Europe (22)](sv-tidszoner-europe.json) | 22 | 5 KB | [CSV](sv-tidszoner-europe_SV.csv) | [Excel](sv-tidszoner-europe_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-europe/) |
| [Tidszoner – Pacific (12)](sv-tidszoner-pacific.json) | 12 | 3 KB | [CSV](sv-tidszoner-pacific_SV.csv) | [Excel](sv-tidszoner-pacific_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-pacific/) |
| [Tidszoner – Africa (9)](sv-tidszoner-africa.json) | 9 | 3 KB | [CSV](sv-tidszoner-africa_SV.csv) | [Excel](sv-tidszoner-africa_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-africa/) |
| [Tidszoner – Indian (7)](sv-tidszoner-indian.json) | 7 | 3 KB | [CSV](sv-tidszoner-indian_SV.csv) | [Excel](sv-tidszoner-indian_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-indian/) |
| [Tidszoner – Atlantic (6)](sv-tidszoner-atlantic.json) | 6 | 2 KB | [CSV](sv-tidszoner-atlantic_SV.csv) | [Excel](sv-tidszoner-atlantic_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-atlantic/) |
| [Tidszoner – Antarctica (2)](sv-tidszoner-antarctica.json) | 2 | 2 KB | [CSV](sv-tidszoner-antarctica_SV.csv) | [Excel](sv-tidszoner-antarctica_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-antarctica/) |
| [Tidszoner – Etc (2)](sv-tidszoner-etc.json) | 2 | 2 KB | [CSV](sv-tidszoner-etc_SV.csv) | [Excel](sv-tidszoner-etc_SV.xlsx) | [View](https://listbase.org/sv/tech/sv-tidszoner-etc/) |

## Quick Start

```bash
# List all technology datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="tech") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/tech/sv-emoji-namn.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/tech/)
