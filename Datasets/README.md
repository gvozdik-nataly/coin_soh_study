# Datasets

Список публичных датасетов, использованных в исследовании.

| # | Датасет | Ссылка | Кратко |
|---|---------|--------|--------|
| 1 | **CALCE** (University of Maryland) | https://calce.umd.edu/data#CS2 | LCO/graphite, ячейки CS2_35–38 (Xiu-model, PINN4SOH) |
| 2 | **Mendeley Data** (LIR2025H, 45 coin cells, Landt CT3001A) | https://data.mendeley.com/datasets/m8w8sjk3vm/2 | пример запуска PINN-ohmage (Max_model) |
| 3 | **EMPA — Autonomous Robotic Battery Platform** (NMC622 coin cells, Zenodo) | https://doi.org/10.5281/zenodo.15481956 | основной внешний датасет исследования |
| 4 | **55 NCM батареек (XJTU / wang-fujin)** | https://zenodo.org/records/10963339 | PINN4SOH (XJTU protocol) |
| 5 | **NASA Li-ion Battery Aging Datasets** (PCoE) | https://data.nasa.gov/dataset/li-ion-battery-aging-datasets | Krith-модель, Xiu-RUL |
| 6 | **SINTEF CR2032** (первичная Li-MnO2, разряд 11 мА) | https://zenodo.org/records/15069341 | второй источник PINN-ohmage (SINTEF, parquet) |

Собственные данные исследования: `Dataset_IOC` (47 ячеек NMC622, протокол cycling + отдельные reference-циклы < 1 мА каждые ~25) и слитый датасет EMPA+IOC (см. отчёты).
