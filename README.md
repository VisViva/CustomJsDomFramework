Выполнил все пункты. На освоение БЭМ ушло бы несколько дней, поэтому я решил написать свой фреймворк с нуля, чтобы быстрее выполнить задание. На клиентской стороне не использовалась ни одна библиотека и нет никаких зависимостей. На сервере использовал NodeJs, MongoDb, Mongoose, Q и Gulp для сборки. Можно конечно много еще понаписать, но мне кажется, в рамки задания уложился. Большое спасибо, жду вашего ответа.

Чтобы запустить проект, сначала необходимо установить все зависимости npm:

  npm install

Потом надо собрать запаковать скрипты и стили с помощью gulp:

  gulp

И наконец, запустить сервак (http://localhost:8080/):

  node server.js


  

// ------------------------------ //

Реализовать таблицу с сортировкой и догрузкой данных.

- В некоторых колонках нужно применить форматирование данных:
  - Округление чисел с запятой.
  - Значения со знаком выводить разным цветом: меньше 0 - красным, больше 0 - синим.
  - Форматирование ссылок.
  - Булевые значения отображать в человекочитаемом виде (такие колонки не нужно сортировать).
- Данных может быть более 100 тыс. Для реализации задания можно ограничиться меньшим количеством.
-  Количество колонок может быть произвольным, но не менее 5-ти.
-  Выбранная сортировка должна запоминаться.
-  Данные нужно получать с сервера на node.js.
-  Архитектура клиентского решение должна быть объектно ориентирована.
-  Можно использовать jQuery и любые БЭМ библиотеки.
-  Использовать другие фреймворки на стороне интерфейса не допускается.
-  Использовать плагины, реализующие таблицу, так же не допускается.
-  Результат нужно выложить на github.

Дополнительное задание (не обязательное)

-  Реализовать возможность выбирать колонки для отображения и указывать их порядок.
-  Первая колонка должна быть зафиксирована.
-  Выбранные колонки должны запоминаться.
