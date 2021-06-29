# Отчёт о тестировании IntelliJ IDEA

## Краткое описание

29.06.2021 - 29.06.2021 было проведено компонентное, функциональное тестирование приложения IntelliJ IDEA.

На тестирование затрачено: 1 час 

В результате тестирования выявлены следующие дефекты:
* [Банковская карта с 13 цифрами не проходит валидацию](https://github.com/Tatiana-Arhipova/creditcard-validator/issues/3)
* [Банковская карта с 15 цифрами не проходит валидацию](https://github.com/Tatiana-Arhipova/creditcard-validator/issues/2)
* [Банковская карта с 19 цифрами не проходит валидацию](https://github.com/Tatiana-Arhipova/creditcard-validator/issues/1)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты :
* [тест-кейс](https://docs.google.com/spreadsheets/d/1nL_ZZAB8pcAlOQWpTTMe29U6tRz0TImeyWzrb0ocTI0/edit?usp=sharing)
 


В качестве тестовых данных использовались данные: https://www.getcreditcardnumbers.com/credit-card-generator  
https://www.freeformatter.com/credit-card-number-generator-validator.html: 
* 4716501634080323 ожидаемый результат Result is OK
* 5324746653650727 ожидаемый результат Result is OK
* 3541693750186340 ожидаемый результат Result is OK
* 4556295697608 ожидаемый результат Result is OK
* 4556607698922 ожидаемый результат Result is OK
* 4532663751913 ожидаемый результат Result is OK
* 345591345434684 ожидаемый результат Result is OK
* 377872978430384 ожидаемый результат Result is OK
* 210084482466653 ожидаемый результат Result is OK
* 4024007106094476599 ожидаемый результат Result is OK
* 4485008339271185129 ожидаемый результат Result is OK
* 3542056598567575570 ожидаемый результат Result is OK

Тестирование производилось в следующем окружении:
* Windows 10, 64-разрядная ОС
* Java 11.0.11
