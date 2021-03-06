## Задание 
> Для разрабатываемой Вами базы данных составить, отладить и проверить 25 инструкции обработки данных, руководствуясь примерами. Для составления запроса с использованием рекурсивного обобщенного табличного выражения требуется модифицировать одну из таблиц таким образом, чтобы в этой таблице был определен внешний ключ, ссылающийся на саму таблицу.

1. Инструкция `SELECT`, использующая предикат сравнения.
2. Инструкция `SELECT`, использующая предикат `BETWEEN`.
3. Инструкция `SELECT`, использующая предикат `LIKE`.
4. Инструкция `SELECT`, использующая предикат `IN` с вложенным подзапросом.
5. Инструкция `SELECT`, использующая предикат `EXISTS` с вложенным подзапросом.
6. Инструкция `SELECT`, использующая предикат сравнения с квантором.
7. Инструкция `SELECT`, использующая агрегатные функции в выражениях столбцов.
8. Инструкция `SELECT`, использующая скалярные подзапросы в выражениях столбцов.
9. Инструкция `SELECT`, использующая простое выражение `CASE`.
10. Инструкция `SELECT`, использующая поисковое выражение `CASE`.
11. Создание новой временной локальной таблицы из результирующего набора данных инструкции `SELECT`. 
12. Инструкция `SELECT`, использующая вложенные коррелированные подзапросы в качестве производных таблиц в предложении `FROM`.
13. Инструкция `SELECT`, использующая вложенные подзапросы с уровнем вложенности 3.
14. Инструкция `SELECT`, консолидирующая данные с помощью предложения `GROUP BY`, но без предложения `HAVING`.
15. Инструкция `SELECT`, консолидирующая данные с помощью предложения `GROUP BY` и  предложения `HAVING`.
16. Однострочная инструкция `INSERT`, выполняющая вставку в таблицу одной строки значений.
17. Многострочная инструкция `INSERT`, выполняющая вставку в таблицу результирующего набора данных вложенного подзапроса.
18. Простая инструкция `UPDATE`.
19. Инструкция `UPDATE` со скалярным подзапросом в предложении `SET`.
20. Простая инструкция `DELETE`.
21. Инструкция `DELETE` с вложенным коррелированным подзапросом в предложении `WHERE`.
22. Инструкция `SELECT`, использующая простое обобщенное табличное выражение.
23. Инструкция `SELECT`, использующая рекурсивное обобщенное табличное выражение.

В запросе 24 продемонстрировать использование операторов `PIVOT` и `UNPIVOT` в предложении `FROM` инструкции `SELECT`
- [пример](http://msdn.microsoft.com/ru-ru/library/ms177410(v=SQL.105).aspx)

В запросе 25 продемонстрировать использование инструкции `MERGE`
- [пример](http://msdn.microsoft.com/ru-ru/library/bb510625.aspx)
