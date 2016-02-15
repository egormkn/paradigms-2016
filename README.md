Тесты к курсу «Парадигмы программирования»
====

[Условия домашних заданий](http://www.kgeorgiy.info/courses/java-intro/homeworks.html)

Домашнее задание 1. Хэширование
----

Модификации
 * *Простая*
    * Класс должен иметь имя `CalcSHA256` и подсчитывать [SHA-256](https://en.wikipedia.org/wiki/Secure_Hash_Algorithm)
    * [Исходный код тестов](java/hash/CalcSHA256Test.java)
    * [Откомпилированные тесты](artifacts/hash/CalcSHA256Test.jar)

Для того, чтобы протестировать исходную программу:

 1. Скачайте тесты ([CalcMD5Test.jar](artifacts/hash/CalcMD5Test.jar))
 * Откомпилируйте `CalcMD5.java`
 * Проверьте, что создался `CalcMD5.class`
 * В каталоге, в котором находится `CalcMD5.class` выполните команду 
    ```
       java -jar <путь к CalcMD5Test.jar>
    ```
    * Например, если `CalcMD5Test.jar` находится в текущем каталоге, выполните команду 
    ```
        java -jar CalcMD5Test.jar
    ```
    
Исходный код тестов: 

* [CalcMD5Test.java](java/hash/CalcMD5Test.java), 
* [HashChecker.java](java/hash/HashChecker.java)
