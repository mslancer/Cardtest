# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11/07/2021 - 11/07/2021 было проведено "Дымовое тестирование" приложения Credit Card Number Validator.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующий дефект:
* [issues]( https://github.com/mslancer/Cardtest/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* IntelliJ IDEA
* Техническое задание
* Тест-кейс

В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* 4929702390092766 - Программа выдает результат
  Result is OK
* 4916505118021214 - Программа выдает результат
  Result is OK
* 4532059148410282433-  Программа выдает результат
  Result is OK

Тестирование производилось в следующем окружении:
* Windows 10
* Java 11
* IntelliJ IDEA
