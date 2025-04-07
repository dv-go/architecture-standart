# 📘 Проект: Цифровая трансформация депозитного направления в банке «Стандарт»

Этот репозиторий содержит материалы по архитектурной проработке MVP открытия депозитов онлайн и сопутствующих изменений в ИТ-инфраструктуре банка «Стандарт» в рамках цифровой трансформации.

---

## 📁 Task1 — Карта IT-ландшафта и схема интеграции

**Описание:**  
Проведен анализ организационной структуры, бизнес-возможностей и IT-систем.  
Построены:
- Карта текущего IT-ландшафта (draw.io)
- Схема интеграции с акцентом на систему АБС (PlantUML + PNG)

**Содержимое:**
- [`Task1/Текущий IT-ландшафт.drawio`](Task1/Текущий%20IT-ландшафт.drawio)
- [`Task1/Схема интеграции приложений.drawio`](Task1/Схема%20интеграции%20приложений.drawio)

---

## 📁 Task2 — FURPS+ таблица требований

**Описание:**  
Сформирована таблица требований на этапе MVP открытия депозитов онлайн.  
Включены функциональные, нефункциональные и архитектурно-значимые требования, с выравниванием по FURPS+.

**Содержимое:**
- [`Task2/FURPS.md`](Task2/FURPS.md)

---

## 📁 Task3 — Архитектурное решение по MVP

**Описание:**  
Подготовлен ADR с архитектурным решением по MVP открытия депозитов.  
Включены диаграммы C4 (уровень 1 и 2), описание компонентов, Use Cases, альтернативы и объёмы разработки.

**Содержимое:**
- [`Task3/ADR.md`](Task3/ADR.md)
- [`Task3/C4_level_1.puml`](Task3/C4_level_1.puml)
- [`Task3/C4_level_1.png`](Task3/C4_level_1.png)
- [`Task3/C4_level_2.puml`](Task3/C4_level_2.puml)
- [`Task3/C4_level_2.png`](Task3/C4_level_2.png)

---

## 📁 Task4 — Расширение: передача ставок в кол-центр

**Описание:**  
Подготовлен ADR по расширению архитектуры для передачи ставок в кол-центр.  
Добавлена RoadMap на 12 месяцев с учётом MVP и будущих улучшений.

**Содержимое:**
- [`Task4/ADR_Transfer_Rates_to_CallCenter.md`](Task4/ADR_Transfer_Rates_to_CallCenter.md)
- [`Task4/C4_Context_TransferRates.puml`](Task4/C4_Context_TransferRates.puml)
- [`Task4/C4_Context_TransferRates.png`](Task4/C4_Context_TransferRates.png)
- [`Task4/C4_Containers_TransferRates.puml`](Task4/C4_Containers_TransferRates.puml)
- [`Task4/C4_Containers_TransferRates.png`](Task4/C4_Containers_TransferRates.png)
- [`Task4/RoadMap_bank_Standart.drawio`](Task4/RoadMap_bank_Standart.drawio)

---

## 📌 Примечания

- Все диаграммы уровня C4 выполнены в PlantUML и экспортированы в PNG.
- Все .drawio-файлы готовы к редактированию в diagrams.net
- Архитектурные решения оформлены в формате ADR, как рекомендовано шаблоном курса.
