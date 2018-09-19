# Практические задачки для Python

1. Написать функцию, которая будет строить полную иерархию пути:
* вход: `['usr', 'local', 'bin']`
* выход: `['/', '/usr', '/usr/local', '/usr/local/bin']`

2. Написать функцию, которая будет суммировать N массивов поэлементно:
* вход: `[1, 2, 3, 4], [5, 6, 7, 8], [9, 10, 11, 12]`
* выход: `[15, 18, 21, 24]`

3. Написать функцию, которая будет выдавать свободные промежутки из интервала `[0, 100]`:
* вход: `[10, 20], [30, 40], [60, 80]`
* выход: `[0-9], [21, 29], [41, 59], [81, 100]`

4. Написать функцию, которая аггрегирует значения в словарях:
* вход: `[{a: 10}, {'a': 20}, {'a': 5, 'b': 10}, {'b': 30, 'c': 25, 'd': 'foo'}, {'d': 'bar'}]`
* выход: `[{'a': 35, 'b': 40, 'c': 25, 'd': 'foobar'}]`

5. Написать функцию, которая объединяет несколько словарей в один по определенному ключу:
* вход: `{"id": 1, "a": 10}, {"id": 1, "b": 20}, {"id: 1, "c": 30}`
* выход: `{"id": 1, "a": 10, "b": 20, "c": 30}`
