# Tid och kalender (Time & Calendar)

8 datasets — 3,778 records

> Browse at [listbase.org/sv/time/](https://listbase.org/sv/time/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Svenska helgdagar och helgdagsaftnar — alla kategorier (1990–2030)](sv-helgdagar-alla-kategorier.json) | 3,460 | 2489 KB | [CSV](sv-helgdagar-alla-kategorier_SV.csv) | [Excel](sv-helgdagar-alla-kategorier_SV.xlsx) | [View](https://listbase.org/sv/time/sv-helgdagar-alla-kategorier/) |
| [Svenska helgdagar — flerspråkig (SV/DE/EN, 2020–2030, openpotato)](sv-helgdagar-flersprakig.json) | 143 | 65 KB | [CSV](sv-helgdagar-flersprakig_SV.csv) | [Excel](sv-helgdagar-flersprakig_SV.xlsx) | [View](https://listbase.org/sv/time/sv-helgdagar-flersprakig/) |
| [Månadsnamn per kalender (CLDR på svenska)](sv-kalendermanader.json) | 74 | 13 KB | [CSV](sv-kalendermanader_SV.csv) | [Excel](sv-kalendermanader_SV.xlsx) | [View](https://listbase.org/sv/time/sv-kalendermanader/) |
| [Helgdagar och flaggdagar i Sverige](sv-helgdagar.json) | 32 | 11 KB | [CSV](sv-helgdagar_SV.csv) | [Excel](sv-helgdagar_SV.xlsx) | [View](https://listbase.org/sv/time/sv-helgdagar/) |
| [Tidsperioder](sv-tidsperioder.json) | 27 | 4 KB | [CSV](sv-tidsperioder_SV.csv) | [Excel](sv-tidsperioder_SV.xlsx) | [View](https://listbase.org/sv/time/sv-tidsperioder/) |
| [Veckodagar, kvartal, dagsperioder och eror – namn på svenska (CLDR)](sv-veckodagar-kvartal-eror.json) | 23 | 5 KB | [CSV](sv-veckodagar-kvartal-eror_SV.csv) | [Excel](sv-veckodagar-kvartal-eror_SV.xlsx) | [View](https://listbase.org/sv/time/sv-veckodagar-kvartal-eror/) |
| [Månader](sv-manader.json) | 12 | 2 KB | [CSV](sv-manader_SV.csv) | [Excel](sv-manader_SV.xlsx) | [View](https://listbase.org/sv/time/sv-manader/) |
| [Veckodagar](sv-veckodagar.json) | 7 | 1 KB | [CSV](sv-veckodagar_SV.csv) | [Excel](sv-veckodagar_SV.xlsx) | [View](https://listbase.org/sv/time/sv-veckodagar/) |

## Quick Start

```bash
# List all time & calendar datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="time") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/time/sv-helgdagar-alla-kategorier.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/time/)
