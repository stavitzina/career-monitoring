# Состояние ротации

last_batch_used: 5
next_batch: 1
last_run_date: 2026-08-13

Routine при каждом запуске: смотрит next_batch, берёт этот батч из companies.md,
после запуска обновляет last_batch_used/next_batch (по кругу 1→2→3→4→5→1...) и last_run_date,
коммитит изменения.
