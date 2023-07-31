Regjur 14

Регистрация нового пользователя (юр лицо) с введенными невалидными данными в поле "Название организации" (данные об организации)

* Тестовые данные: 
  
  Предусловия:
  
  1. Создан тестовый электронный ящик(и)
  
  2. Открыта форма регистрации и выбрана вкладка "Юридическое лицо" 
     
     (ссылка на прод [Регистрация](https://stroyrem-nn.ru/user/register) и на тест [Регистрация](https://test2.stroyrem-nn.ru/user/register))
  
  3. Все поля заполнены валидными данными, кроме поля "Название организации"

* Шаги:
1. Ввести в поле "Название организации" (Данные об организации) специальные символы (например, !@#$%^&*()_+) и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Поле "Название организации" в рамке красного цвета и появляется надпись "Введите корректные данные"

2. Ввести в поле "Название организации" (Данные об организации) html тэги <> и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Поле "Название организации" в рамке красного цвета и появляется надпись "Введите корректные данные"

3. Ввести в поле "Название организации" (Данные об организации) вредоносный код (например,<script>alert(“I hacked this!”)</script>) и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Поле "Название организации" в рамке красного цвета и появляется надпись "Введите корректные данные"

4. Ввести в поле "Название организации" (Данные об организации) sql инъекция (например, FOO'); DROP TABLE NUMBER) и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Поле "Название организации" в рамке красного цвета и появляется надпись "Введите корректные данные"

5. Ввести в поле "Название организации" (Данные об организации) пробелы и нажать кнопку "Зарегистрироваться"
   
   **ОР:** Появляется ошибка "empty_name_company" и регистрация не проходит
* Постусловия: удалить тестовые данные на тестовом сервере/выйти из профиля, если регистрация проходит успешно

Автор: Татьяна

* Тестовый сервер Chrome version 115.0.5790.102 (Official Build) (64-bit)

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:20 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:43 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:54 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:04 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:12 | PASS      | Татьяна |                               |

* Продовый сервер Chrome version 115.0.5790.102 (Official Build) (64-bit)

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:20 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:43 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:55 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:04 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:13 | PASS      | Татьяна |                               |

- Тестовый сервер Firefox version 115.0.2 (64-bit)

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:21 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:44 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:55 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:05 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:13 | PASS      | Татьяна |                               |

- Продовый сервер Firefox version 115.0.2 (64-bit)

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:22 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:45 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:56 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:06 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:14 | PASS      | Татьяна |                               |

- Тестовый сервер Мобильное устройство Huawei Mate 10 PRO EMUI 12.0.0.225

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:22 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:46 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:56 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:06 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:15 | PASS      | Татьяна |                               |

- Продовый сервер Мобильное устройство Huawei Mate 10 PRO EMUI 12.0.0.225

Тест выполнен

| №   | Дата       | Время | Результат | Имя     | Баг № Trello                  |
| --- | ---------- | ----- | --------- | ------- | ----------------------------- |
| 1   | 2023-07-24 | 14:23 | FAIL      | Татьяна | https://trello.com/c/ttgsqgfS |
| 2   | 2023-07-24 | 14:47 | FAIL      | Татьяна | https://trello.com/c/a5wpum0B |
| 3   | 2023-07-24 | 14:57 | FAIL      | Татьяна | https://trello.com/c/SwxGNuLt |
| 4   | 2023-07-24 | 15:07 | FAIL      | Татьяна | https://trello.com/c/IBUQOYJQ |
| 5   | 2023-07-24 | 15:16 | PASS      | Татьяна | https://trello.com/c/76bRoDNB |