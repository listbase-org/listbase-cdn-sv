# Underhållning (Entertainment)

14 datasets — 1,363 records

> Browse at [listbase.org/sv/entertainment/](https://listbase.org/sv/entertainment/)

## Datasets

| Name | Records | Size | CSV | Excel | Preview |
|------|---------|------|-----|-------|---------|
| [TV-kanalflöden (Swedish TV channel feeds)](sv-tv-kanaler-feeder.json) | 792 | 220 KB | [CSV](sv-tv-kanaler-feeder_SV.csv) | [Excel](sv-tv-kanaler-feeder_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-feeder/) |
| [Svenska TV-kanaler](sv-tv-kanaler.json) | 255 | 93 KB | [CSV](sv-tv-kanaler_SV.csv) | [Excel](sv-tv-kanaler_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler/) |
| [Serie-TV-kanaler (Series TV channels)](sv-tv-kanaler-serier.json) | 66 | 33 KB | [CSV](sv-tv-kanaler-serier_SV.csv) | [Excel](sv-tv-kanaler-serier_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-serier/) |
| [Underhållningskanaler (Entertainment TV channels)](sv-tv-kanaler-underhallning.json) | 64 | 33 KB | [CSV](sv-tv-kanaler-underhallning_SV.csv) | [Excel](sv-tv-kanaler-underhallning_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-underhallning/) |
| [Filmkanaler (Movies TV channels)](sv-tv-kanaler-film.json) | 51 | 24 KB | [CSV](sv-tv-kanaler-film_SV.csv) | [Excel](sv-tv-kanaler-film_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-film/) |
| [Komedikanaler (Comedy TV channels)](sv-tv-kanaler-komedi.json) | 35 | 20 KB | [CSV](sv-tv-kanaler-komedi_SV.csv) | [Excel](sv-tv-kanaler-komedi_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-komedi/) |
| [Allmänna TV-kanaler (General TV channels)](sv-tv-kanaler-allmanna.json) | 19 | 10 KB | [CSV](sv-tv-kanaler-allmanna_SV.csv) | [Excel](sv-tv-kanaler-allmanna_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-allmanna/) |
| [Barnkanaler (Kids TV channels)](sv-tv-kanaler-barn.json) | 17 | 10 KB | [CSV](sv-tv-kanaler-barn_SV.csv) | [Excel](sv-tv-kanaler-barn_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-barn/) |
| [Dokumentärkanaler (Documentary TV channels)](sv-tv-kanaler-dokumentar.json) | 17 | 10 KB | [CSV](sv-tv-kanaler-dokumentar_SV.csv) | [Excel](sv-tv-kanaler-dokumentar_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-dokumentar/) |
| [Klassiska TV-kanaler (Classic TV channels)](sv-tv-kanaler-klassiker.json) | 11 | 7 KB | [CSV](sv-tv-kanaler-klassiker_SV.csv) | [Excel](sv-tv-kanaler-klassiker_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-klassiker/) |
| [Animationskanaler (Animation TV channels)](sv-tv-kanaler-animation.json) | 10 | 8 KB | [CSV](sv-tv-kanaler-animation_SV.csv) | [Excel](sv-tv-kanaler-animation_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-animation/) |
| [Livsstilskanaler (Lifestyle TV channels)](sv-tv-kanaler-livsstil.json) | 10 | 7 KB | [CSV](sv-tv-kanaler-livsstil_SV.csv) | [Excel](sv-tv-kanaler-livsstil_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-livsstil/) |
| [Matlagningskanaler (Cooking TV channels)](sv-tv-kanaler-matlagning.json) | 10 | 7 KB | [CSV](sv-tv-kanaler-matlagning_SV.csv) | [Excel](sv-tv-kanaler-matlagning_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-matlagning/) |
| [Nyhetskanaler (News TV channels)](sv-tv-kanaler-nyheter.json) | 6 | 4 KB | [CSV](sv-tv-kanaler-nyheter_SV.csv) | [Excel](sv-tv-kanaler-nyheter_SV.xlsx) | [View](https://listbase.org/sv/entertainment/sv-tv-kanaler-nyheter/) |

## Quick Start

```bash
# List all entertainment datasets
curl https://cdn.sv.listbase.org/index.json | jq '.datasets[] | select(.category=="entertainment") | .id'

# Fetch a dataset
curl https://cdn.sv.listbase.org/entertainment/sv-tv-kanaler-feeder.json
```

---

[← Back to all categories](../README.md) · [Browse on ListBase](https://listbase.org/sv/entertainment/)
