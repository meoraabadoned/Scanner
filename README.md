# Scanner

[Сетевая папка с документацией](https://drive.google.com/open?id=1gRm0BXvvrmWOKySY41TpRYbHzGeOJ61t)

## Участники

| Учебная группа | Имя пользователя | ФИО                      |
|----------------|------------------|--------------------------|
| 161-331        | @loir1998        | Алещенко А.А.            |
| 161-331        | @shrimpdevs      | Павленко А.А.            |

## Личный вклад участников

### Алещенко А.А.

Исследовала структуры интернет-магазинов.
Исследовала методы синтаксического анализа сайтов.
Разработала скрипты для автоматизации выборки ссылок из каталогов интернет-магазинов.
Тестировала функционал.
Вносила правки.
Готовила сопроводительную документацию.

Общий объем потраченного времени: 115 часов.

### Павленко А.А.

Исследовал методы синтаксического анализа сайтов.
Выбирал библиотеки.
Составил архитектуру программного обеспечения.
Разработал основной программный модуль.
Тестировал.
Вносил правки.
Готовил сопроводительную документацию.

Общий объем потраченного времени: 127 часов.

**Используемые библиотеки**

> BeatifulSoup4

> Requests

**Файлы**
- parser.py - исполнительный файл 
- settings.py - файл с путями к текстовым файлам
- log.txt - лог-файл
- stats.txt - статистика работы программы
- test.txt - файл с тестовым каталогом сайтов
- old.txt - каталог европейских интернет-магазинов 
- cis.txt - каталог интернет-магазинов СНГ
- international.txt - каталог интернет-магазинов со всего мира
- resources.txt - каталог всех интернет-магазинов

**Установка библиотек**
```Shell
pip install bs4
pip install requests
```

**Запуск программы**
```Shell
python.exe .\parser.py
```
