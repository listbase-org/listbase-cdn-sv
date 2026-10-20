# Mat (Food & Nutrition)

4 datasets — 18,687 records

> Browse at [listbase.org/sv/food/](https://listbase.org/sv/food/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Restauranger i Sverige](sv-restauranger.json) | 10,492 | 1050 KB | [CSV](sv-restauranger_SV.csv) | [Excel](sv-restauranger_SV.xlsx) | [View](https://listbase.org/sv/food/sv-restauranger/) |
| [Snabbmatsställen (Fast food)](sv-snabbmat.json) | 3,751 | 372 KB | [CSV](sv-snabbmat_SV.csv) | [Excel](sv-snabbmat_SV.xlsx) | [View](https://listbase.org/sv/food/sv-snabbmat/) |
| [Snabbmatsrestauranger i Sverige](sv-snabbmatsrestauranger.json) | 3,750 | 372 KB | [CSV](sv-snabbmatsrestauranger_SV.csv) | [Excel](sv-snabbmatsrestauranger_SV.xlsx) | [View](https://listbase.org/sv/food/sv-snabbmatsrestauranger/) |
| [Bagerier i Sverige](sv-bagerier.json) | 694 | 72 KB | [CSV](sv-bagerier_SV.csv) | [Excel](sv-bagerier_SV.xlsx) | [View](https://listbase.org/sv/food/sv-bagerier/) |

## Quick Start

```bash
# List all food & nutrition datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="food") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/food/sv-restauranger.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/food/)
