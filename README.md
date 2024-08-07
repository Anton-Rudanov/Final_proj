# Финальный проект 
Дипломная работа по автоматизации на Пайтон. Сайт https://www.chitai-gorod.ru/

## Стек
- selenium
- requests
- pytest
- allure

### Структура проекта:
1. API тесты
- поиск по названию
- поиск по ID
- добавление книги в закладки
- добавление книги в корзину
- очистка корзины
- просмотр личных данных пользователя
- изменение имени пользователя в его профиле
2. UI тесты
- открыть сайт Читай-город
- принять cookie
- поиск книги по названию
- добавить все книги в корзину и посчитать их количество
- переход в корзину

### Шаги
1. Склонировать репозиторий 'git clone https://github.com/Anton-Rudanov/Final_proj.git'
2. Установить все зависимости
3. Запустить тесты 'pytest'


### Библиотеки
- pip install pytest
- pip install selenium
- pip install webdriver-manager
- pip install request
- pip install allure-pytest