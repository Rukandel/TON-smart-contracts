# Ton smart contracts exapmle 
Проект создан в процессе изучения блокчейна TON и языка Tact. Использовался как шпаргалка во время хакатона Hack a TON

# Содержание
contracts - исходный код всех смарт-контрактов проекта и их зависимостей.
wrappers - классы-оболочки (реализующие контракт из ton-core) для контрактов, включая любые примитивы десериализации и функции компиляции.
tests - тесты для контрактов.
scripts - скрипты, используемые в проекте, в основном скрипты развертывания.

## Установка
### 1. Скачать репозиторий

### 2. Установить зависимости:
`$ yarn install`

### 3. Сборка
`$ yarn build`

### 4. Тестирование 
`$ yarn test`

### 5. Запуск
`$ yarn start`

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost`

If you have previously deployed you may want to append `--reset` at the end:

`$ npx hardhat ignition deploy ignition/modules/Factory.js --network localhost --reset`

### 6. Запустить клиент
`$ npm run dev`
