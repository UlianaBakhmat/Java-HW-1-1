
 ## ОТЧЕТ О ТЕСТИРОВАНИИ KeyValidator

## Краткое описание

04.06.2020 - 04.06.2020 было проведено: 
дымовое тестирование, функциональное тестирование, регрессионное тестирование, тестирование сборки, 
тестирование установки, конфигурационное тестирование, приложения KeyValidator.

На тестирование затрачено: 40 минут

В результате тестирования выявлены следующие дефекты:

*https://github.com/UlianaBakhmat/Java-HW-1-1/issues/1
* 
* В результате тестирования выявлено: предоставленные ключи имеют ошибки как валидные, так и невалидные. 
  
Подробнее об ошибках:

Валидные ключи:
* Result for 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* Result for 80b427f8-92cd-3aae-ba04-03927fbe17c6: FAIL
* Result for b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* Result for 387eedc6-12e9-3b32-9881-63b6b5e85317: FAIL
* Result for c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

Невалидные ключи:
* Result for 18252235-78e0-44a5-8720-556f0c7da17a: FAIL
* Result for e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* Result for b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* Result for c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL
* Result for 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1: OK


## Описание процесса тестирования
В процессе тестирования использовались следующие артефакты:
* Git Bash
* Github
* Visual Studio Code
В качестве тестовых данных использовались данные из GitHub:  
https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D0%BA%D0%BB%D1%8E%D1%87%D0%B8-%D0%B4%D0%BB%D1%8F-%D0%BF%D1%80%D0%BE%D0%B2%D0%B5%D1%80%D0%BA%D0%B8

Ключи для проверки:

Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* Windows x64
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
* Visual Studio Code (Version 1.45.1 (user setup)
* Chrome (83.0.4103.116)
* Git Bash 2.26.2.windows.1


