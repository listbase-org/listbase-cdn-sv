# Vetenskap (Science)

2 datasets — 9,347 records

> Browse at [listbase.org/sv/science/](https://listbase.org/sv/science/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Demografiska statistikområden (DeSO)](sv-deso.json) | 5,984 | 934 KB | [CSV](sv-deso_SV.csv) | [Excel](sv-deso_SV.xlsx) | [View](https://listbase.org/sv/science/sv-deso/) |
| [Regionala statistikområden (RegSO)](sv-regso.json) | 3,363 | 557 KB | [CSV](sv-regso_SV.csv) | [Excel](sv-regso_SV.xlsx) | [View](https://listbase.org/sv/science/sv-regso/) |

## Quick Start

```bash
# List all science datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="science") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/science/sv-deso.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/science/)
