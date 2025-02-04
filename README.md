# Домашнее задание "Инфраструктура"

## Требования:

Для запуска примеров необходимо установить [NodeJS](https://nodejs.org/en/download/) 16 или выше.

## Как добавить коммиты с помощью npm run commit:

Вместо использования стандартной команды `git commit -m "сообщение коммита"`, вы можете использовать встроенный в проект скрипт commit, который помогает структурировать ваши сообщения коммитов. 

```sh
# Добавить изменения для коммита
git add .

# Запустить помощник для коммита
npm run commit
```

После запуска `npm run commit`, откроется интерактивный CLI для первоначального (или подробного) сообщения коммита. Этот инструмент гарантирует, что ваши сообщения коммитов соответствуют ожидаемому формату.

## Как запустить unit-тесты:

```sh
# Установить зависимости
npm ci

# Запустить приложение
npm start
```

## Как запустить e2e тесты:

```sh
# Скачать браузеры
npx playwright install

# Запустить тесты
npm run e2e
```

## Как запустить модульные тесты:

```sh
npm test
```

