# ListBase CDN — Svenska (sv)

Open dataset collection for **Svenska** (Swedish).
455 datasets across 20 categories with 2,262,118 total records.

> Browse and download at [https://listbase.org/sv/](https://listbase.org/sv/)

## Categories

| Category | Datasets |
|----------|----------|
| [Kultur och religion (Culture & Religion)](culture/) | 9 |
| [Ekonomi (Economy)](economy/) | 1 |
| [Utbildning (Education)](education/) | 3 |
| [Underhållning (Entertainment)](entertainment/) | 14 |
| [Miljö (Environment)](environment/) | 13 |
| [Finans och handel (Finance & Trade)](finance/) | 5 |
| [Mat (Food & Nutrition)](food/) | 4 |
| [Geografi (Geography)](geography/) | 70 |
| [Hälsa (Health)](health/) | 4 |
| [Språk (Language)](language/) | 2 |
| [Politik (Politics)](politics/) | 21 |
| [Referens (Reference)](reference/) | 215 |
| [Vetenskap (Science)](science/) | 2 |
| [Samhälle (Society)](society/) | 1 |
| [Sport (Sports)](sports/) | 2 |
| [Teknik (Technology)](tech/) | 11 |
| [Tid och kalender (Time & Calendar)](time/) | 8 |
| [Turism (Tourism)](tourism/) | 8 |
| [Transport](transport/) | 41 |
| [Enheter och mått (Units & Measurements)](units/) | 21 |

## Usage

### Browse on the web
Visit [listbase.org/sv/](https://listbase.org/sv/) to search, preview, and download in Excel, CSV, or PDF.

### Fetch via CDN
```bash
# Dataset index (metadata only)
curl https://cdn.sv.listbase.org/index.json

# Full dataset (JSON)
curl https://cdn.sv.listbase.org/geography/th-central-provinces.json

# Download as Excel or CSV
curl -O https://cdn.sv.listbase.org/geography/th-central-provinces_SV.xlsx
curl -O https://cdn.sv.listbase.org/geography/th-central-provinces_SV.csv

# Build dump (metadata + sample rows, gzipped)
curl https://cdn.sv.listbase.org/dump.json.gz | gunzip
```

### Use in JavaScript
```js
const res = await fetch('https://cdn.sv.listbase.org/geography/th-central-provinces.json');
const data = await res.json();
console.log(data.name);    // "ภาคกลาง — จังหวัดในภาคกลาง"
console.log(data.rows);    // [{ ... }, ...]
```

## File Structure

```
├── index.json              # Dataset index (metadata + file info)
├── dump.json.gz            # Build dump (metadata + 20 sample rows per dataset)
├── {category}/
│   ├── README.md           # Category overview
│   ├── {dataset}.json      # Full dataset with rows
│   ├── {dataset}_SV.csv   # CSV download
│   └── {dataset}_SV.xlsx  # Excel download
```

## Dataset JSON Format

Each `.json` file contains:

| Field | Description |
|-------|-------------|
| `id` | Unique dataset identifier |
| `name` | Dataset name |
| `description` | What this dataset contains |
| `category` | Category (e.g. geography, finance) |
| `source` | Data source attribution |
| `updated` | Last updated date |
| `record_count` | Number of records |
| `columns` | Column definitions (key, label, type) |
| `rows` | Array of data records |

## License

Data is provided under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
See individual dataset `source` fields for original data attribution.

---

Part of [ListBase](https://listbase.org) — Free Reference Tables & Lists
