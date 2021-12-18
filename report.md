# Отчёт о тестировании приложения Credit Card Number Validator

## Краткое описание

14.01.2021 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 0,3ч.

В результате тестирования выявлен следующий дефект:

[Карты типов AMEX и Diners Club не проходят проверку на валидность](https://github.com/viktoriia287/Java_1.1.2/issues/1)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* Техническое задание.

В качестве тестовых данных использовались данные:
* [Техническое задание](https://github.com/netology-code/javaqa-homeworks/tree/master/intro (часть: Задача №2 - Credit Card Number Validator));
* [Генератор валидных номеров карт](https://www.freeformatter.com/credit-card-number-generator-validator.html).

Для более точного тестирования были использованы карты из разных платежных систем, в т.ч.: 
* МИР;
* Amex;
* DinerClub;
* MasterCard;
* Visa;
* MasterCard;
* Maestro.

## Тестирование производилось в следующем окружении:

* ОС: Windows, 64;
* версия Java: 11.0.9.1.
