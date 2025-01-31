---
sidebar_position: 2
---

# Описание общих типов

## Market

Определяет рынок, на котором торгуется инструмент. Принимает следующие значения:

- `Stock` - фондовый рынок Московской биржи;
- `Forts` - срочный рынок Московской биржи;
- `Spbex` - Санкт-Петербургская биржа;
- `Mma` - фондовый рынок США;
- `Ets` - валютный рынок Московской биржи;
- `Bonds` - рынок облигаций Московской биржи;
- `Options` - рынок опционов Московской биржи.

## BuySell

Определяет тип операции: покупка или продажа. Принимает следующие значения:

- `Buy` - покупка,
- `Sell`- продажа.

## OrderValidBefore

Обозначает время действия заявки. Тип условия определяет значение поля `type`, которое принимает следующие параметры:

- `TillEndSession` - заявка действует до конца сессии;
- `TillCancelled` - заявка действует, пока не будет отменена;
- `ExactTime` - заявка действует до указанного времени. Параметр `time` должен быть задан.
