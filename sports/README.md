# Sport (Sports)

2 datasets — 2,729 records

> Browse at [listbase.org/sv/sports/](https://listbase.org/sv/sports/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Idrottsanläggningar (Sports centres)](sv-idrottsanlaggningar.json) | 2,671 | 275 KB | [CSV](sv-idrottsanlaggningar_SV.csv) | [Excel](sv-idrottsanlaggningar_SV.xlsx) | [View](https://listbase.org/sv/sports/sv-idrottsanlaggningar/) |
| [Sportkanaler (Sports TV channels)](sv-tv-kanaler-sport.json) | 58 | 24 KB | [CSV](sv-tv-kanaler-sport_SV.csv) | [Excel](sv-tv-kanaler-sport_SV.xlsx) | [View](https://listbase.org/sv/sports/sv-tv-kanaler-sport/) |

## Quick Start

```bash
# List all sports datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="sports") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/sports/sv-idrottsanlaggningar.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/sports/)
