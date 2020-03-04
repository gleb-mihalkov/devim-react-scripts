# Devim React Scripts

Коллекция скриптов и утилит для разработки проектов на React. Содержит:

* Набор npm-команд.
* Настройки для `typescript`, `babel`, `eslint`.
* Декларации типов для `typescript`.

## Установка

```bash
npm i -D @devim/react-scripts
```

## Использование

Для того, чтобы использовать скрипты в своем проекте, следует добавить их в секцию `scripts` своего `package.json`.

```json
{
  // ...
  "scripts": {
    "build": "@devim/react-scripts:build",
    "start": "@devim/react-scripts:start",
    "serve": "@devim/react-scripts:serve",
    // ...
  }
  // ...
}
```

Кроме того, пакет предоставляет настройки для `typescript`, пресет для `babel` и конфигурацию `eslint`. Чтобы использовать настройки `typescript`, подключите их в своём `tsconfig.json`:

```json
{
  "extends": ["@devim/react-scripts"]
}
```

Для добавления настроек `babel` расширьте свою конфигурацию `.babelrc`:

```json
{
  "extends": ["@devim/react-scripts"]
}
```

Для расширения правил `eslint` можно поступить аналогичным образом:

```json
{
  "extends": ["@devim/react-scripts"]
}
```

## Описание скриптов

*Раздел находится в разработке.*

## Описание процесса сборки

*Раздел находится в разработке.*
