## Тестове завдання для Frontend Developer

Мета:
Створити веб сайт використовуючи React, який буде працювати з апі (цим проектом). 

Вимоги:
- React, TypeScript
- Підключене апі
- На сайті мають бути представлені такі сторінки
-- Головна сторінка - Сторінка з список туторіалів
-- Сторінка з додаванням і редагуванням туторіала
-- Сторінка з детальною інформацією по певному туторіалу
- Між сторінками потрібно мати можливість переходити по гіперсилкам. Тобто має бути кнопка - сторити туторіал, а в таблиці має бути кнопка - відредагувати туторіал, і можливість подивитись деталі певного туторіалу без редагування.

Дозволено
- Використовувати будь які інші бібліотеки
- Вимог до дизайну і функціоналу не має, переходи між сторінками можна зробити в будь який спосіб
- Використання Redux та будь яких інших плагінів повністью на розсуд розробника виходячи з обмежень по часу встановленого на задачу.
- В рамках задачі представлено проект з апі (поточний), який потрібно запустити і використовувати його апі без жодної модифікації.


Кроки
0. Розархівувати бекенд проект і встановити npm пакети. 

1. Встановити базу даних монго або використати існуючу
- Встановити Mongo Server (https://www.mongodb.com/try/download/community)
АБО (в випадку використання не локального серверу бази даних)
-. Отримати рядок підключення (по замовчуванню це mongodb://localhost:27017/testTask)
-. Відкрити файл config/db.config.js і замінити url значення на отриманий рядок підключення.

2. Запустити поточний проект npm start
3. Використовуючи Postman або в будь який інший спосіб відправити запит localhost:8080/api/tutorials та впевнитись що тримано відповідь від сервера в вигляді пустого масиву та 200-го статус коду.

4. Можна приступати до розробки нового проекту - фронтенду.

------------------------------------------------------
Деталі про сигнатуру методів, адреси та приклади виконання запитів описанні нижче.
Список доступних шляхів:

/api/tutorials: GET, POST, DELETE
/api/tutorials/:id: GET, PUT, DELETE
/api/tutorials/published: GET

Перед адресою потрібно додати http://localhost:8080


Приклади запитів з тілом відповіді
Створення туторіала
https://www.bezkoder.com/wp-content/uploads/2020/02/node-express-mongodb-crud-rest-api-create.png


Отримання певного туторіала
https://www.bezkoder.com/wp-content/uploads/2020/02/node-express-mongodb-crud-rest-api-find-by-id.png


Оновлення певного туторіала
https://www.bezkoder.com/wp-content/uploads/2020/02/node-express-mongodb-crud-rest-api-update.png


Отримання всіх туторіалів з фільтрацією
https://www.bezkoder.com/wp-content/uploads/2020/02/node-express-mongodb-crud-rest-api-find-by-field.png


Отримання всіх опублікованих туторіалів
https://www.bezkoder.com/wp-content/uploads/2020/02/node-express-mongodb-crud-rest-api-find-by-active.png