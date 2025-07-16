# Данные для языка `lang` от вендора <Vendor>

## raw/
Содержит монокорпуса различных размеров:
- lang_mono_100k.txt
- lang_mono_1M.txt
- lang_mono_10M.txt
- lang_mono_100M.txt
- lang_mono_1T.txt

## stats/
Один файл lang_population.csv со столбцами:
- year
- total_speakers_global
- total_speakers_rf
- source_name
- source_url

## keyboard/
JSON‑файлы с вариантами раскладок:
- lang_key_default.json
- lang_key_4rows.json
- lang_key_complex.json

## frequencies/
lang_monocorpus_freq.csv — частотности символов.

## mapping/
lang_key_mapping.json — маппинг расширенных букв на русские клавиши.

## metadata.json
Обязательные поля: version, source, date_collected, contact, description.
Допускаются дополнительные поля.

---  
**Подсказка:** можно добавлять аудиоданные, фонетику, примеры предложений, графики и др.
