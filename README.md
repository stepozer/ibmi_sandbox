# Демонстрационные приложения на языке RPGLE

Содержит примеры программ для IBM i 7.5 на языке RPGLE, примеры работы с базой данных, массивами и т.д.

## Структура проекта

- `deploy` - java программа для деплоя приложения на публичный IBM i сервер (https://www.pub400.com/).
- `hello` - программы для демонстрации синтаксиса языка:
  - `demoarr.rpgle` - программа генерирует случайный массив, сортирует его методом пузырька и печатает на экран.
  - `demoarr.rpgle` - программа вычисляет сумму квадратов (использует FOR) а также вычисляет сумму квадратных корней (использует DO).
  - `hw.rpgle` - программа печатает фразу "Hello World!!!" на экран.
- `exchange` - программа для работы с таблицей курсов валют.