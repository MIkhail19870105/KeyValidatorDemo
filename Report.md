# Отчёт о тестировании KeyValidator

## Краткое описание

26.04.2020 - 26.04.2020 было проведено тестирование установки и функциональное тестирование приложения [KeyValidator](https://github.com/MIkhail19870105/KeyValidatorDemo/blob/master/KeyValidator.class).

На тестирование затрачено: 1 hour

## Чек лист:
1. Выполнить инструкцию по установке OpenJDK11 убедиться в том что она работает под вашу ОС [Инструкция по установке OpenJDK](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md): **Passed**
2. Запустить приложение KeyValidator убедиться в совместимости с Java 11: **Passed**
3. Используя [Руководство пользования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator) убедиться в работоспособности приложения: **Failed**

В результате тестирования выявлены следующие дефекты:
* [Bug#1 Некоторые валидные ключи не прошли проверку](https://github.com/MIkhail19870105/KeyValidatorDemo/issues/1#issue-607027362)
* [Bug#2 Некоторые невалидные ключи не прошли проверку](https://github.com/MIkhail19870105/KeyValidatorDemo/issues/2#issue-607028887)


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Bug Report в Issues проекта

В качестве тестовых данных использовались данные из [Руководство пользования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md#%D1%80%D1%83%D0%BA%D0%BE%D0%B2%D0%BE%D0%B4%D1%81%D1%82%D0%B2%D0%BE-%D0%B8%D1%81%D0%BF%D0%BE%D0%BB%D1%8C%D0%B7%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F-keyvalidator):

## Ключи для проверки

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

## Тестирование производилось в следующем окружении:
* Windows 10 Pro X64
* openjdk version "11.0.7" 2020-04-14
* OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.7+10)
* OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.7+10, mixed mode)
* git version 2.26.0
