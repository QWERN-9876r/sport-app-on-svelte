Запуск WEB приложения.
Сначала необходимо запустить сервер:

cd server
npm start

В другом терминале запускаем фронтенд:

cd TrainingApp
npm start -- --host

По ссылке http://localhost:5173 запуститься svelte приложение.

Сайт создан для домашних тренировок. Со стороны клиента используется Svelte (SSR), а на сервере используется express, данные хранятся в формате json, а не в BD т.к целью разработчика было освоение Svelte, а не backend разработка.
