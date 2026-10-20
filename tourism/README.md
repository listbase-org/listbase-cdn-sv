# Turism (Tourism)

8 datasets — 11,391 records

> Browse at [listbase.org/sv/tourism/](https://listbase.org/sv/tourism/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [Turistinformation (Tourist information points)](sv-turistinformation.json) | 3,624 | 383 KB | [CSV](sv-turistinformation_SV.csv) | [Excel](sv-turistinformation_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-turistinformation/) |
| [Offentlig konst (Public artworks)](sv-offentlig-konst.json) | 2,107 | 211 KB | [CSV](sv-offentlig-konst_SV.csv) | [Excel](sv-offentlig-konst_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-offentlig-konst/) |
| [Hotell (Hotels)](sv-hotell.json) | 1,658 | 173 KB | [CSV](sv-hotell_SV.csv) | [Excel](sv-hotell_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-hotell/) |
| [Sevärdheter i Sverige](sv-sevardheter.json) | 1,310 | 134 KB | [CSV](sv-sevardheter_SV.csv) | [Excel](sv-sevardheter_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-sevardheter/) |
| [Campingplatser i Sverige](sv-campingplatser.json) | 1,182 | 126 KB | [CSV](sv-campingplatser_SV.csv) | [Excel](sv-campingplatser_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-campingplatser/) |
| [Utsiktsplatser (Viewpoints)](sv-utsiktsplatser.json) | 529 | 54 KB | [CSV](sv-utsiktsplatser_SV.csv) | [Excel](sv-utsiktsplatser_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-utsiktsplatser/) |
| [Utsiktspunkter i Sverige](sv-utsiktspunkter.json) | 529 | 54 KB | [CSV](sv-utsiktspunkter_SV.csv) | [Excel](sv-utsiktspunkter_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-utsiktspunkter/) |
| [Gästgiverier (Guest houses)](sv-gastgiverier.json) | 452 | 49 KB | [CSV](sv-gastgiverier_SV.csv) | [Excel](sv-gastgiverier_SV.xlsx) | [View](https://listbase.org/sv/tourism/sv-gastgiverier/) |

## Quick Start

```bash
# List all tourism datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="tourism") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/tourism/sv-turistinformation.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/tourism/)
