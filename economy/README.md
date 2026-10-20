# Ekonomi (Economy)

1 datasets — 13,815 records

> Browse at [listbase.org/sv/economy/](https://listbase.org/sv/economy/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Svenska yrken (Swedish occupations)](sv-yrken.json) | 13,815 | 1261 KB | [CSV](sv-yrken_SV.csv) | [Excel](sv-yrken_SV.xlsx) | [View](https://listbase.org/sv/economy/sv-yrken/) |

## Quick Start

```bash
# List all economy datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="economy") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/economy/sv-yrken.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/economy/)
