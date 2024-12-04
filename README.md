# Домашнее задание по теме "Декораторы"

Задание: Декораторы в Python

Цель задания:

Освоить механизмы создания декораторов Python.
Практически применить знания, создав функцию декоратор и обернув ею
другую функцию.

Задание:

Напишите 2 функции:
1. Функция, которая складывает 3 числа (```sum_three```)
2. Функция декоратор (```is_prime```), которая распечатывает "```Простое```",
   если результат 1ой функции будет простым числом и "```Составное```" в
   противном случае.

Пример:
```
result = sum_three(2, 3, 6)
print(result)
```

Результат консоли:
```
Простое
11
```

Примечания:
> 1. Не забудьте написать внутреннюю функцию ```wrapper``` в ```is_prime```
> 2. Функция ```is_prime``` должна возвращать ```wrapper```
> 3. ```@is_prime``` - декоратор для функции ```sum_three```

Файл module_9_7.py и загрузите его на ваш GitHub репозиторий. В решении
пришлите ссылку на него.

Успехов!