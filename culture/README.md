# Kultur och religion (Culture & Religion)

9 datasets — 6,382 records

> Browse at [listbase.org/sv/culture/](https://listbase.org/sv/culture/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Religiösa byggnader i Sverige](sv-religiosa-byggnader.json) | 4,567 | 468 KB | [CSV](sv-religiosa-byggnader_SV.csv) | [Excel](sv-religiosa-byggnader_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-religiosa-byggnader/) |
| [Bibliotek i Sverige](sv-bibliotek.json) | 662 | 71 KB | [CSV](sv-bibliotek_SV.csv) | [Excel](sv-bibliotek_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-bibliotek/) |
| [Museer i Sverige (Museums in Sweden)](sv-museer.json) | 502 | 106 KB | [CSV](sv-museer_SV.csv) | [Excel](sv-museer_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-museer/) |
| [Teatrar i Sverige](sv-teatrar.json) | 312 | 33 KB | [CSV](sv-teatrar_SV.csv) | [Excel](sv-teatrar_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-teatrar/) |
| [Biografer i Sverige](sv-biografer.json) | 249 | 26 KB | [CSV](sv-biografer_SV.csv) | [Excel](sv-biografer_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-biografer/) |
| [Kloster i Sverige](sv-kloster.json) | 51 | 18 KB | [CSV](sv-kloster_SV.csv) | [Excel](sv-kloster_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-kloster/) |
| [Moskéer i Sverige](sv-moskeer.json) | 18 | 8 KB | [CSV](sv-moskeer_SV.csv) | [Excel](sv-moskeer_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-moskeer/) |
| [Världsarv i Sverige](sv-varldsarv-unesco.json) | 15 | 16 KB | [CSV](sv-varldsarv-unesco_SV.csv) | [Excel](sv-varldsarv-unesco_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-varldsarv-unesco/) |
| [Synagogor i Sverige](sv-synagogor.json) | 6 | 4 KB | [CSV](sv-synagogor_SV.csv) | [Excel](sv-synagogor_SV.xlsx) | [View](https://listbase.org/sv/culture/sv-synagogor/) |

## Quick Start

```bash
# List all culture & religion datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="culture") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/culture/sv-religiosa-byggnader.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/culture/)
