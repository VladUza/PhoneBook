## Задача 1. Разработка через тестирование
Описание
Так как мы прошли Test Driven Development, попытаемся разработать минимальную программу с помощью этого подхода.

Вам нужно разработать класс телефонной книги, которая позволяет:

add — добавить имя с номером. Метод должен возвращать количество контактов после добавления, при этом гарантируется, что не будут добавляться повторяющиеся имена;
findByNumber — найти имя по номеру без полного перебора;
findByName — найти номер по имени без полного перебора;
printAllNames — вывести все имена в алфавитном порядке без необходимости проводить сортировку.
Реализация
Класс телефонной книги нужно разрабатывать поэтапно — по одному методу за раз. Следуйте техникам TDD. Таким образом, разработка должна проходить по этапам:

Создать пустой мавен-проект.
Создать пустой класс PhoneBook.
Создать пустой класс тестов PhoneBookTest.
Сделать коммит с сообщением Initial commit.
Создать пустой метод-заглушку add в классе PhoneBook, который только возвращает 0.
Создать тест или тесты на метод add в классе тестов PhoneBookTest.
Убедиться, что всё компилируется и тесты не проходят. Сделать коммит с сообщением Stub and tests for add.
Реализовать метод add так, чтобы все тесты проходили.
Сделать коммит с сообщением add implemented.
Создать пустой метод-заглушку findByNumber в классе PhoneBook, который только возвращает null.
Создать тест или тесты на метод findByNumber в классе тестов PhoneBookTest.
Убедиться, что всё компилируется и тесты не проходят. Сделать коммит с сообщением Stub and tests for findByNumber.
Реализовать метод findByNumber так, чтобы все тесты проходили.
Сделать коммит с сообщением findByNumber implemented.
...
После того, как вся функциональность реализована, сделайте пуш в новый репозиторий. Убедитесь, что все тесты проходят и у вас сделаны все требуемые в задании коммиты.