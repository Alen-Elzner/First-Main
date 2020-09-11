## Краткое описание

11.09.2020 - 11.09.2020 было проведено дымовое тестирование (только валидные значения) приложения Credit Card Number Validator.

### На тестирование затрачено: 30мин

### В результате тестирования выявлены следующие дефекты:

* [№1 Валидный номер карты VISA не проходит валидацию.](https://github.com/Alen-Elzner/First-Main/issues/1);
* [№2 Валидные номера карт American Express (AMEX) не проходят валидацию](https://github.com/Alen-Elzner/First-Main/issues/2);
* [№3 Валидный номер карты Discover не проходит валидацию.](https://github.com/Alen-Elzner/First-Main/issues/3);
* [№4 Валидный номер карты JCB не проходит валидацию.](https://github.com/Alen-Elzner/First-Main/issues/4);
* [№5 Валидные номера карт Diners Club - Carte Blanche не проходят валидацию](https://github.com/Alen-Elzner/First-Main/issues/5);
* [№6 Валидные номера карт Diners Club - International не проходят валидацию](https://github.com/Alen-Elzner/First-Main/issues/6);

## Описание процесса тестирования

### В процессе тестирования использовались следующие артефакты:

1. [Описание задания](https://github.com/netology-code/javaqa-homeworks/tree/master/intro)

### В качестве тестовых данных использовались данные из [Credit Card Number Generator & Validator](https://www.freeformatter.com/credit-card-number-generator-validator.html):

**Валидные номера карт**:

VISA:
* 4485419025889278
* 4929266473041587
* 4485501051535662296   

MasterCard:
* 5139570049125102
* 2221003850714406
* 5388813338099457

American Express (AMEX):
* 345439315854020    
* 377699587873989    
* 341669645543604   

Discover:
* 6011759446219755
* 6011537286914085
* 6011199553692772940 

JCB:
* 3535906265083564
* 3531279764040004
* 3545814391359868619  

Diners Club - North America:
* 5501396861405491
* 5412088042714630
* 5432850184773369

Diners Club - Carte Blanche:
* 30177116270786
* 30049091191198
* 30265745700990

Diners Club - International:
* 36015874544691
* 36782219679207
* 36320150390649

Maestro:
* 6761295048369922
* 6759457031540190
* 5018103419986378

Visa Electron:
* 4026514308713967
* 4917560673183791
* 4508587254359297

InstaPayment:
* 6393737292256905
* 6398101358580424
* 6388294716669633

### Тестирование производилось в следующем окружении:

* Windows 8.1 професиональная build 9600
* openjdk version "11.0.8" 2020-07-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.8+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.8+10, mixed mode)
* IntelliJ IDEA Community 2020.2.1

