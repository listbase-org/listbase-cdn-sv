# Finans och handel (Finance & Trade)

5 datasets — 4,319 records

> Browse at [listbase.org/sv/finance/](https://listbase.org/sv/finance/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Caféer i Sverige](sv-kafeer.json) | 3,566 | 361 KB | [CSV](sv-kafeer_SV.csv) | [Excel](sv-kafeer_SV.xlsx) | [View](https://listbase.org/sv/finance/sv-kafeer/) |
| [SWIFT/BIC-koder — Sverige](sv-swift-koder.json) | 523 | 72 KB | [CSV](sv-swift-koder_SV.csv) | [Excel](sv-swift-koder_SV.xlsx) | [View](https://listbase.org/sv/finance/sv-swift-koder/) |
| [Bankomater i Sverige](sv-bankomater.json) | 153 | 16 KB | [CSV](sv-bankomater_SV.csv) | [Excel](sv-bankomater_SV.xlsx) | [View](https://listbase.org/sv/finance/sv-bankomater/) |
| [Banker i Sverige — clearingnummer-register](sv-banker.json) | 64 | 16 KB | [CSV](sv-banker_SV.csv) | [Excel](sv-banker_SV.xlsx) | [View](https://listbase.org/sv/finance/sv-banker/) |
| [Oljekraftverk i Sverige](sv-oljekraftverk.json) | 13 | 10 KB | [CSV](sv-oljekraftverk_SV.csv) | [Excel](sv-oljekraftverk_SV.xlsx) | [View](https://listbase.org/sv/finance/sv-oljekraftverk/) |

## Quick Start

```bash
# List all finance & trade datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="finance") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/finance/sv-kafeer.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/finance/)
