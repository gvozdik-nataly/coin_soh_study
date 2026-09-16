# coin_soh_study

Исследование предсказания State of Health (SOH) малых литий-ионных аккумуляторов
(coin cells) на публичных и собственных датасетах. Основные отчёты — HTML-страницы
в рабочей реплике исследования (см. ниже).

## Структура репозитория

```
ML-models/       — вставленные (git submodule) репозитории моделей
  ├── BatteryML   (Microsoft, ICLR 2024)      — бенчмарк SOH/RUL
  ├── PINN4SOH    (Wang et al., Nature Comm.) — physics-informed сеть деградации
  └── Xiu-RUL     (XiuzeZhou)                 — Transformer / AttMoE RUL
Datasets/README.md — ссылки на публичные датасеты
```

Подтянуть подмодули:

```bash
git clone --recursive https://github.com/gvozdik-nataly/coin_soh_study
cd coin_soh_study
git submodule update --init --recursive
```

Сводные отчёты исследования (HTML): `final4_report.html`, `comparison_report_7models.html`,
`final_soh_report.html` — ведутся в рабочей копии; дублируются по запросу в `report/`.
