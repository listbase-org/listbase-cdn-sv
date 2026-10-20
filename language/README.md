# Språk (Language)

2 datasets — 789 records

> Browse at [listbase.org/sv/language/](https://listbase.org/sv/language/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Världens språk](sv-sprak.json) | 591 | 54 KB | [CSV](sv-sprak_SV.csv) | [Excel](sv-sprak_SV.xlsx) | [View](https://listbase.org/sv/language/sv-sprak/) |
| [Världens skriftsystem (ISO 15924 / CLDR på svenska)](sv-skriftsystem.json) | 198 | 17 KB | [CSV](sv-skriftsystem_SV.csv) | [Excel](sv-skriftsystem_SV.xlsx) | [View](https://listbase.org/sv/language/sv-skriftsystem/) |

## Quick Start

```bash
# List all language datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="language") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/language/sv-sprak.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/language/)
