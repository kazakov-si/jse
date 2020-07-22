# Task Manager

#### Резервный репозиторий

- Резервный репозиторий расположен на [github](https://https://github.com/kazakov-si/jse)

#### 1. Требования к  SOFTWARE

- Java OpenJDK 11;
- Apache Maven 3.6.1.

#### 2. Используемый стек технологий

- Java SE;
- Apache Maven.

#### 3. Разработчик

- Автор: *Казаков Сергей*
- e-mail [личный]: *kazak605@gmail.com*
- e-mail [рабочий]: *kazakov_si@nlmk.com*

#### 4. Команды для сборки приложения

```mvn clean``` - Удаление всех созданных в процессе сборки артефактов

```mvn compile``` - Компилирование проекта

```mvn test``` - Тестирование с помощью JUnit тестов

```mvn install``` - Копирование .jar (war , ear) в локальный репозиторий

```mvn deploy``` - Публикация файла в удалённый репозиторий


#### 5. Команды для запуска приложения

Команда для запуска приложения:
```bash
java -jar target/task-manager-1.0.0.jar
```  

Терминальные команды:

* help - Отображение списка терминальных команд;

* version - Отображение версии программы;

* about - Отображение информации об разработчике;

* exit - Выход из программы.

Пример запуска приложения с теринальной командой:

```bash
java -jar target/jse-04-1.0-SNAPSHOT.jar help
```
