# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

11.05.21 - 11.05.21 было проведено функциональное тестирование приложения Credit Card Number Validator.

На тестирование затрачено: 1 час.

В результате тестирования выявлены следующие дефекты:
* [Не валидируются банковские карты если их номер больше 16 цифр.](https://github.com/Masikoshka/J_DZ_1.1/issues/1#issue-887605138)
* [Не валидируются банковские карты если их номер меньше 16 цифр.](https://github.com/Masikoshka/J_DZ_1.1/issues/2#issue-887648317)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Спецификация Credit Card Number Validator.](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)
* [Код разработчика.](https://github.com/Masikoshka/J_DZ_1.1/blob/master/src/Main.java)
* [Чек-лист.](https://github.com/netology-code/javaqa-homeworks/tree/master/intro#%D0%BB%D0%B5%D0%B3%D0%B5%D0%BD%D0%B4%D0%B0)

В качестве тестовых данных использовались:
* [Credit Card Number Generator & Validator.](https://www.freeformatter.com/credit-card-number-generator-validator.html)

Тестирование производилось в следующем окружении:
* Windows 10, версия: 20H2, разрядность 64.
* Версия Java: 11.