# Utbildning (Education)

3 datasets — 8,995 records

> Browse at [listbase.org/sv/education/](https://listbase.org/sv/education/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Skolor i Sverige](sv-skolor.json) | 4,626 | 476 KB | [CSV](sv-skolor_SV.csv) | [Excel](sv-skolor_SV.xlsx) | [View](https://listbase.org/sv/education/sv-skolor/) |
| [Förskolor i Sverige](sv-forskolor.json) | 4,333 | 464 KB | [CSV](sv-forskolor_SV.csv) | [Excel](sv-forskolor_SV.xlsx) | [View](https://listbase.org/sv/education/sv-forskolor/) |
| [Sweden — Universitet & högskolor (Universities)](sv-universitet.json) | 36 | 11 KB | [CSV](sv-universitet_SV.csv) | [Excel](sv-universitet_SV.xlsx) | [View](https://listbase.org/sv/education/sv-universitet/) |

## Quick Start

```bash
# List all education datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="education") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/education/sv-skolor.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/education/)
