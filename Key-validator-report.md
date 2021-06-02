# Отчёт о тестировании Key Validator

## Краткое описание

02.06.21 - 02.06.21 было проведено функциональное тестирование приложения Key Validator.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>
* <ссылка на описание дефекта>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [тест кейсы](https://docs.google.com/spreadsheets/d/1Q5VMujk7q-Xc6RHxt-UnK2tmnoAbK1YCf8oAa_Qt70I/edit?usp=sharing)

В качестве тестовых данных использовались данные [из руководства пользователя](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
#### Валидные ключи
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - result is ok
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 - result is ok  
* b295bc63-9f03-3b4b-af80-969b39f8c262 - result is ok  
* 387eedc6-12e9-3b32-9881-63b6b5e85317 - result is ok  
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - result is ok  
#### Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a - result is fail  
* e66075b6-ddad-445e-baf6-161b3289522b - result is fail  
* b6d53250-f07e-4352-a293-6102ddf7f1ca - result is fail  
* c2bc778a-1cb9-46c6-b435-0489649d2a42 - result is fail  
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - result is fail  

Тестирование производилось в следующем окружении:
* macOS Big Sur ver.11.3.1
* Java ver.11.0.10
* IntelliJ IDEA CE 2021.1.2