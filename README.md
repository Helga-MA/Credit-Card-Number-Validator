# Отчёт о тестировании "Credit Card Number Validator"

## Краткое описание

13.08.2021 - 13.08.2021 было проведено дымовое тестирование приложения "Credit Card Number Validator".

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* [Банковские карты не проходят валидацию из-за ограничения в количестве символов](https://github.com/Helga-MA/Credit-Card-Number-Validator/issues/1)


В качестве тестовых данных использовались данные [freeformatter.com](https://www.freeformatter.com/credit-card-number-generator-validator.html):
* VISA с номером 4916752323901554 проходит валидацию
* VISA c номером 4539373183345018879 проходит валидацию
* Diners Club - Carte Blanche с номером 30267763193942 проходит валидацию
* JCB c номером 3532450635997119893 проходит валидацию
* American Express (AMEX) с номером 347822803470870 проходит валидацию

Тестирование производилось в следующем окружении:
* Operating system: Windows 10
* Java 11.0.11.9