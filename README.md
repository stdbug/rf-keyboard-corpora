# rf-keyboard-corpora

Репозиторий для хранения корпусных данных и метаданных по языкам РФ.

## Структура

- data/lang/vendor/raw/ — сырые монокорпуса (`lang_mono_<size>.txt`)
- data/lang/vendor/stats/ — статистика носителей (`lang_population.csv`)
- data/lang/vendor/keyboard/ — раскладки (`lang_key_default.json`, `lang_key_4rows.json`, `lang_key_complex.json`, при необходимости `lang_layout.json`)
- data/lang/vendor/frequencies/ — частотности (`lang_monocorpus_freq.csv`)
- data/lang/vendor/mapping/ — маппинг букв (`lang_key_mapping.json`)
- data/lang/vendor/metadata.json — обязательный манифест набора
- data/lang/vendor/README.md — описание всех файлов и особенностей

> **Примечание:** вместо `lang` используйте ISO-код языка (например, `tyv`, `tat`).  
> Частотности собираются по наибольшему монокорпусу каждого языка.  
> Хеш‑суммы опциональны — добавляйте при необходимости.
