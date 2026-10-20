# Hälsa (Health)

4 datasets — 2,978 records

> Browse at [listbase.org/sv/health/](https://listbase.org/sv/health/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Vårdcentraler i Sverige](sv-vardcentraler.json) | 1,196 | 136 KB | [CSV](sv-vardcentraler_SV.csv) | [Excel](sv-vardcentraler_SV.xlsx) | [View](https://listbase.org/sv/health/sv-vardcentraler/) |
| [Apotek i Sverige](sv-apotek.json) | 1,007 | 102 KB | [CSV](sv-apotek_SV.csv) | [Excel](sv-apotek_SV.xlsx) | [View](https://listbase.org/sv/health/sv-apotek/) |
| [Coronalexikon (smittord)](sv-coronalexikon.json) | 563 | 65 KB | [CSV](sv-coronalexikon_SV.csv) | [Excel](sv-coronalexikon_SV.xlsx) | [View](https://listbase.org/sv/health/sv-coronalexikon/) |
| [Sjukhus i Sverige](sv-sjukhus.json) | 212 | 24 KB | [CSV](sv-sjukhus_SV.csv) | [Excel](sv-sjukhus_SV.xlsx) | [View](https://listbase.org/sv/health/sv-sjukhus/) |

## Quick Start

```bash
# List all health datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="health") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/health/sv-vardcentraler.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/health/)
