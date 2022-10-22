# HTTP аутентификация
## Текст задания
### Цель работы
Спроектировать и разработать систему авторизации пользователей на протоколе HTTP
## Ход работы
## 1. [Пользовательский интерфейс](https://www.figma.com/file/bLl3gl2IcQ8VxjLdRN7Ixd/HTTP-Authorization?node-id=0%3A1)
## 2. Пользовательские сценарии работы
## 3. API сервера и хореография
## 4. Структура базы данных
| id | login | hash | secword |
|:---|:------|:-----|:--------|
- id: INT, AUTO_INCREMENT, PRIMARY KEY;
Уникальный идентификатор пользователя
- login: VARCHAR, 70;
логин пользователя
- hash: VARCHAR, 62;
хэшированный пароль
- secword: VARCHAR, 62;
секретное слово для восстановления пароля
## 5. Алгоритмы
## 6. Примеры HTTP запросов/ответов
