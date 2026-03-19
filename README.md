## Stock Order Automation / Автоматизация заказов поставщикам

###English

Task: calculate the optimal order quantity based on sales history and current stock levels.

Data: export from 1C 

Features:
- calculation of average demand over a selected period
- stock and incoming goods aggregation
- automatic order quantity calculation
- demand spike detection (high sales flag)

Result:
- reduced order preparation time from 2 hours to 15 minutes
- improved stock control (reduced shortages and overstock)

Parameters:
- `season_months` — sales analysis period (default: 3 months)
- `season_multi` — stock coverage multiplier (default: x2)
- `anomaly_threshold` — demand spike threshold (default: x2 of average)

---

##Русский

Задача: рассчитать оптимальный объем заказа на основе истории продаж и текущих остатков.

Данные: выгрузка из 1С 

Функционал:
- расчет среднего спроса за выбранный период
- учет остатков и ожидаемых поставок
- автоматический расчет объема заказа
- выявление всплесков спроса (флаг аномальных продаж)

Результат:
- сокращение времени подготовки заказа с 2 часов до 15 минут
- снижение риска дефицита и избыточных запасов

Параметры:
- `season_months` — период анализа продаж (по умолчанию: 3 месяца)
- `season_multi` — коэффициент запаса (по умолчанию: x2)
- `anomaly_threshold` — порог всплеска спроса (по умолчанию: x2 от среднего)
