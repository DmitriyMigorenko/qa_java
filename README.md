# Sprint_6

Задача: написать юнит тесты для заготовки проекта qa_java

## Стэк:
* Maven
* Java 11
* JUnit 4
* Mockito
* Jacoco


## Тестовые сценарии
Написаны тесты на классы Feline, Cat и Lion.
Класс Lion не зависит от класса Feline благодаря принципу инъекции зависимостей. Достигнуто 100% покрытие тестами вышеупомянутых классов.

## Запуск тестов
* Чтобы запустить тесты использовать команду:
```
mvn clean verify
```