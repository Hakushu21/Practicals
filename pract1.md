# Практическое занятие №1. Введение, основы работы в командной строке

П.Н. Советов, РТУ МИРЭА

Научиться выполнять простые действия с файлами и каталогами в Linux из командной строки. Сравнить работу в командной строке Windows и Linux.

## Задача 1

Вывести отсортированный в алфавитном порядке список имен пользователей в файле passwd (вам понадобится grep).
![image](https://github.com/user-attachments/assets/d6f72ef2-9481-4e0a-815a-ef72847069ef)

## Задача 2

Вывести данные /etc/protocols в отформатированном и отсортированном порядке для 5 наибольших портов, как показано в примере ниже:

```
[root@localhost etc]# cat /etc/protocols ...
142 rohc
141 wesp
140 shim6
139 hip
138 manet
```
![image](https://github.com/user-attachments/assets/69a3d24f-c405-4438-a60b-63a52a0efc28)

## Задача 3

Написать программу banner средствами bash для вывода текстов, как в следующем примере (размер баннера должен меняться!):

```
[root@localhost ~]# ./banner "Hello from RTU MIREA!"
+-----------------------+
| Hello from RTU MIREA! |
+-----------------------+
```

Перед отправкой решения проверьте его в ShellCheck на предупреждения.
![image](https://github.com/user-attachments/assets/3223491b-4df0-40ad-bc1b-5893d2aebd9b)
![image](https://github.com/user-attachments/assets/9f3ea1f0-20bd-4a24-92b3-2845f59db26b)


## Задача 4

Написать программу для вывода всех идентификаторов (по правилам C/C++ или Java) в файле (без повторений).

Пример для hello.c:

```
h hello include int main n printf return stdio void world
```
![image](https://github.com/user-attachments/assets/88717265-17c4-4946-b609-146d612c8927)
![image](https://github.com/user-attachments/assets/702573ee-ea57-4b9a-b44c-35e358dad789)
![image](https://github.com/user-attachments/assets/90e4ab22-6cf6-415f-832e-8c299dd3dab3)

## Задача 5

Написать программу для регистрации пользовательской команды (правильные права доступа и копирование в /usr/local/bin).

Например, пусть программа называется reg:

```
./reg banner
```

В результате для banner задаются правильные права доступа и сам banner копируется в /usr/local/bin.
![image](https://github.com/user-attachments/assets/a302533f-6469-4830-a7c4-18a0169c988e)
D![image](https://github.com/user-attachments/assets/d9fef99b-57a9-422a-824a-a2d29e6a1e27)

## Задача 6

Написать программу для проверки наличия комментария в первой строке файлов с расширением c, js и py.
![image](https://github.com/user-attachments/assets/725d881f-13fc-4d3c-be03-164456c9a3ea)
![image](https://github.com/user-attachments/assets/eb1a6d07-a82f-4131-9b69-928aabe0a5f5)

## Задача 7

Написать программу для нахождения файлов-дубликатов (имеющих 1 или более копий содержимого) по заданному пути (и подкаталогам).
![image](https://github.com/user-attachments/assets/556b326b-da78-42fa-84b5-6fff883402b4)
![image](https://github.com/user-attachments/assets/20754644-7820-497c-af54-ad4641a16173)

## Задача 8

Написать программу, которая находит все файлы в данном каталоге с расширением, указанным в качестве аргумента и архивирует все эти файлы в архив tar.
![image](https://github.com/user-attachments/assets/249bc1d0-a0c8-41c8-8c65-8e834bd4bf8b)
![image](https://github.com/user-attachments/assets/cd7f3193-19e5-4bbe-9b7c-1ffaf726d2fd)

## Задача 9

Написать программу, которая заменяет в файле последовательности из 4 пробелов на символ табуляции. Входной и выходной файлы задаются аргументами.
![image](https://github.com/user-attachments/assets/079d865e-414e-4910-8091-22e276ef297e)
![image](https://github.com/user-attachments/assets/66e3b1be-064c-4da6-b986-a16446afb462)
![image](https://github.com/user-attachments/assets/9df0833e-e8c2-473d-be00-6c54db91de0b)
![image](https://github.com/user-attachments/assets/e05a4fd9-2e3d-441b-8c55-b28e134e475f)

## Задача 10

Написать программу, которая выводит названия всех пустых текстовых файлов в указанной директории. Директория передается в программу параметром. 
![image](https://github.com/user-attachments/assets/8db2c5ce-06ef-4226-ae1d-1deeefd08763)
![image](https://github.com/user-attachments/assets/a1fe5a44-94ca-44db-808e-cc6705c44f95)

## Полезные ссылки

Линукс в браузере: https://bellard.org/jslinux/

ShellCheck: https://www.shellcheck.net/

Разработка CLI-приложений

Общие сведения

https://ru.wikipedia.org/wiki/Интерфейс_командной_строки
https://nullprogram.com/blog/2020/08/01/
https://habr.com/ru/post/150950/

Стандарты

https://www.gnu.org/prep/standards/standards.html#Command_002dLine-Interfaces
https://www.gnu.org/software/libc/manual/html_node/Argument-Syntax.html
https://pubs.opengroup.org/onlinepubs/9699919799/basedefs/V1_chap12.html

Реализация разбора опций

Питон

https://docs.python.org/3/library/argparse.html#module-argparse
https://click.palletsprojects.com/en/7.x/
![Uploading image.png…]()
