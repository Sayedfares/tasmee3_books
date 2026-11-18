# tasmee3_books

Optional tafsir, i'rab and translation books for the Faris (فارس) recitation app. Downloaded on demand by the app.

- `catalog.json` — the books the app offers to download (key, Arabic name, group, size in MB).
- `<key>.json` — a whole book: `{"<surah>:<ayah>": {"text": "..."}}` (translations: `{"t": "..."}`).
- `tafsir/`, `irab-daas/`, `irab-nahhas/` — per-surah files bundled in the app (`<surah>.json`).
- `index.json` — metadata for those three.

Source: quranpedia.net / Quran.com (QUL) data. Each book belongs to its authors and publishers.
