## **Отчёт о тестировании приложения Bank Transaction**
#### Краткое описание
Запущено приложение Bank Transaction, которое считает остаток по счету клиенту после его пополнения.

Предварительно проверено, что соответствующим переменным присвоены валидные (положительные) значения текущего остатка и суммы пополнения (перевода).

Результат работы приложения: отрицательное значение итогового остатка по счету.
#### Описание тестов
Проводилось позитивное, функциональное тестирование функции суммирования текущего остатка и суммы пополнения счета для определения итогового остатка по счету

В качестве тестовых данных использовались данные реальной транзакции:
1. текущий баланс счета клиента = 2 млрд. руб.
1. сумма перевода (пополнения счета) = 500 млн.руб.
#### Результаты:
* 0% успешных/ 100% не успешных тестов
* cсылка на баг-репорт: https://github.com/mona52/Bank-Transact/issues/1#issue-785411906
#### Общие рекомендации
Проверить тип переменной, в которую записывается итоговое значение остатка по счету после пополнения


