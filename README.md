## Тестовое задание

## Необходимо разработать WEB - приложение, обеспечивающее следующие функции:
- Показ пользователю в браузере (Firefox, Chrome последних версий) списка из 2-3 полей с возможностью сортировки и фильтрации.
- Удаление из списка строки  с запросом на удаление.
- Добавление строки в список с запросом на ввод данных для полей списка.

## Требования к приложению:
- Приложение должно использовать для хранения списка MS SQL Server версии от 2008 R2 и выше (необходимо дать пользователю возможность задать параметры подключения (сервер, порт, пользователь, пароль и имя базы данных).
- Приложение должно запускаться локально на машине пользователя (тестовая среда выполнения - Windows 7 и 10).
- Желательный язык приложения (как фронт так и бэк) - JS

## Запуск
- Конфиг `/src/config.js`
- Установка модулей `npm init` (node_modules)
- Новый продакшен билд - `npm run build`
- Запустить продакшен билд `npx serve -s build`
- Запуск в режиме разработки - `npm start`

## Запуск сервера
- Конфиг `/test-task-server/config.js`
- Установка модулей `npm init` (node_modules)
- Запустить сервер `cd test-task-server && npm start`

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).