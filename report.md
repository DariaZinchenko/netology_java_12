# Отчёт о тестировании Credit Card Number Validator

## Краткое описание

22.11.2020 - 22.11.2020 было проведены: дымовое тестирование и функциональное тестирование приложения [Credit Card Number Validator](https://github.com/DariaZinchenko/netology_java_12/blob/main/src/Main.java).

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* [Некорректная валидация номера карты, количество символов в котором не ровно 16](https://github.com/DariaZinchenko/netology_java_12/issues/1)

## Описание процесса тестирования

В качестве тестовых данных использовались номера карт, сгенерированные на сайте [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* 4916424703034 - валидный номер
* 30461665070320 - валидный номер
* 377576361917879 - валидный номер
* 4716431357672133097 - валидный номер
* 2720995562624516 - валидный номер
* 4929496332720598 - валидный номер
* 0000000000000000 - невалидный номер
* АААролпорырпыпра - невалидный номер
* dfhdhjfghlsfjhfh - невалидный номер
* &%&*&%*&*&^%&^%& - невалидный номер
* 492949 332720598 - невалидный номер

Тестирование производилось в следующем окружении:
* версия и разрядность ОС: Windows 10, x64
* версия Java: 11.0.9.1
* другое ПО: IntelliJ IDEA Community
