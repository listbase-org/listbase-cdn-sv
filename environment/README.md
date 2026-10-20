# Miljö (Environment)

13 datasets — 15,288 records

> Browse at [listbase.org/sv/environment/](https://listbase.org/sv/environment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Bergstoppar (Mountain peaks)](sv-bergstoppar.json) | 13,594 | 1344 KB | [CSV](sv-bergstoppar_SV.csv) | [Excel](sv-bergstoppar_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-bergstoppar/) |
| [Kraftverk i Sverige](sv-kraftverk.json) | 662 | 339 KB | [CSV](sv-kraftverk_SV.csv) | [Excel](sv-kraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-kraftverk/) |
| [Vindkraftverk i Sverige](sv-vindkraftverk.json) | 264 | 135 KB | [CSV](sv-vindkraftverk_SV.csv) | [Excel](sv-vindkraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-vindkraftverk/) |
| [Grottöppningar (Cave entrances)](sv-grottoppningar.json) | 202 | 22 KB | [CSV](sv-grottoppningar_SV.csv) | [Excel](sv-grottoppningar_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-grottoppningar/) |
| [Vattenkraftverk i Sverige](sv-vattenkraftverk.json) | 182 | 100 KB | [CSV](sv-vattenkraftverk_SV.csv) | [Excel](sv-vattenkraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-vattenkraftverk/) |
| [Källor (Springs)](sv-kallor.json) | 167 | 18 KB | [CSV](sv-kallor_SV.csv) | [Excel](sv-kallor_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-kallor/) |
| [Solkraftverk (solcellsparker) i Sverige](sv-solkraftverk.json) | 99 | 52 KB | [CSV](sv-solkraftverk_SV.csv) | [Excel](sv-solkraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-solkraftverk/) |
| [Biokraftverk (biobränsle/biomassa) i Sverige](sv-biokraftverk.json) | 40 | 23 KB | [CSV](sv-biokraftverk_SV.csv) | [Excel](sv-biokraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-biokraftverk/) |
| [Batterilager (energilagring) i Sverige](sv-batterilager.json) | 35 | 20 KB | [CSV](sv-batterilager_SV.csv) | [Excel](sv-batterilager_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-batterilager/) |
| [Måttenheter – kategori 'energy' (14)](sv-mattenheter-energy.json) | 14 | 5 KB | [CSV](sv-mattenheter-energy_SV.csv) | [Excel](sv-mattenheter-energy_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-mattenheter-energy/) |
| [Kärnkraftverk i Sverige](sv-karnkraftverk.json) | 13 | 8 KB | [CSV](sv-karnkraftverk_SV.csv) | [Excel](sv-karnkraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-karnkraftverk/) |
| [Avfallskraftverk (avfallsförbränning) i Sverige](sv-avfallskraftverk.json) | 11 | 9 KB | [CSV](sv-avfallskraftverk_SV.csv) | [Excel](sv-avfallskraftverk_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-avfallskraftverk/) |
| [Måttenheter – kategori 'temperature' (5)](sv-mattenheter-temperature.json) | 5 | 3 KB | [CSV](sv-mattenheter-temperature_SV.csv) | [Excel](sv-mattenheter-temperature_SV.xlsx) | [View](https://listbase.org/sv/environment/sv-mattenheter-temperature/) |

## Quick Start

```bash
# List all environment datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="environment") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/environment/sv-bergstoppar.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/environment/)
