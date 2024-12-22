# Команда grep

## Задание 1: Простое задание (разбор по шагам)
Шаги:

1. Создайте текстовый файл ```fruits.txt``` со следующими данными:
```
banana
cherry
apple
apple pie
banana split
cherry tart
```

2. Используйте команду grep для поиска строки, содержащей слово apple:

```bash
grep "apple" fruits.txt
```

  Результат:
```
apple  
apple pie  
```

3. Используйте опцию -i для поиска строки без учёта регистра:

```bash
grep -i "Apple" fruits.txt
```

4. Найдите строки, содержащие слово pie, с указанием номера строки (опция -n):

```bash
grep -n "pie" fruits.txt
```

5. Используйте регулярное выражение для поиска строк, начинающихся с b (опция -E):

```bash
grep -E "^b" fruits.txt
```

## Задача

Условие:

В файле logs.txt находится список логов с разными уровнями важности (INFO, WARNING, ERROR). Ваша задача:

1. Вывести строки, содержащие слово ERROR.
2. Найти строки с уровнями WARNING или ERROR.
3. Посчитать, сколько раз слово INFO встречается в файле.
4. Сохранить строки с ERROR в отдельный файл errors.txt.

Пример файла ```logs.txt```:

```
[INFO] Application started  
[WARNING] Low memory  
[ERROR] File not found  
[INFO] User logged in  
[ERROR] Connection lost  
```

# Ресурсы
1. [Официальная документация grep](https://www.gnu.org/software/grep/manual/grep.html)
2. [Linuxize: Как использовать grep](https://linuxize.com/post/how-to-use-grep-command-to-search-files-in-linux/)
3. [Tutorialspoint: Руководство по grep](https://www.tutorialspoint.com/unix_commands/grep.htm)

### Как успешно сдать работу?
Создать свой репозиторий из шаблона этого. Как это делается - "Use this template" -> "Create a new repository" и сделайте его public.\
\
Находясь уже в своем репозитории - создайте новый файл формата .md и там оформляйте отчет. В отчете опишите все шаги которые вы делали, чтобы получить финальный результат работы.
