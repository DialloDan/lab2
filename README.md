# КПЗ

## Опис призначення бібліотеки

Бібліотека `npm` призначена для спрощення розробки програмного забезпечення на `JavaScript` та `Node.js` шляхом надання готових функцій, модулів і інструментів. Вона дає змогу повторно використовувати вже реалізований код замість створення типових компонентів із нуля.

За допомогою `npm-бібліотек` розробники можуть швидше створювати застосунки, підключати додаткову функціональність, керувати залежностями та підтримувати проєкт у зручному й структурованому вигляді. Бібліотеки встановлюються через менеджер пакетів `npm` та можуть бути інтегровані у власні програмні проєкти.

## Інструкції з запуску

`npm i` (`npm install`) — це щоб завантажити всі необхідні бібліотеки та модулі, описані у файлі `package.json`.

`npm run demo` — це щоб запустити проєкт у демо-режимі.

`npm run build` — це щоб скомпілювати та підготувати проєкт до продакшену.

## Огляд кроків еволюції

Версія 0.1.0 — Додано прості функції з `any`

Версія 0.2.0 — Змінено функції з `any` на функції з базовими типами

Версія 0.3.0 — Додано нову функцію зі складним типом

Версія 0.4.0 — Додано інтерфейс та generic

Версія 0.5.0 — Додано клас `Logger` та змінні оточення (`.env`)

Версія 1.0.0 — Стабілізував публічне API та посилив правила

Версія 2.0.0 — Змінив сигнатуру add

## Приклади використання функцій

Приклад `add`:

`console.log('sum(2.0 ok):', add([5, 6, -8]));`

Результат:

`sum(2.0 ok): 3`

Приклад `capitalize`:

`console.log('capitalize(typed):', capitalize('watermelon'));`

Результат:

`capitalize(typed): Watermelon`

Приклад `formatNumber`:

`console.log('format(ok):', formatNumber(321.456789));`

Результат:

`format(ok): 321.457`

Приклад `groupBy`:

`console.log('group ok:', groupBy(users, 'name'));`

Результат:

```
group ok: {
  Alice: [ { id: 1, name: 'Alice' } ],
  Bob: [ { id: 2, name: 'Bob' } ]
}
```

Приклад `Logger.info`:

`logger.info('Application started');`

Результат:

`[INFO] Application started`

Приклад `Logger.debug`:

`logger.debug('Extra debug info');`

Результат:

`[DEBUG] Extra debug info`

## Нотатка про `.env`

`.env` ключі це:

- APP_PRECISION // number
- LOG_LEVEL // 'silent'|'info'|'debug' string

## Посилання на теги релізів

- [v0.1.0](https://github.com/DialloDan/lab2/tree/v0.1.0)
- [v0.2.0](https://github.com/DialloDan/lab2/tree/v0.2.0)
- [v0.3.0](https://github.com/DialloDan/lab2/tree/v0.3.0)
- [v0.4.0](https://github.com/DialloDan/lab2/tree/v0.4.0)
- [v0.5.0](https://github.com/DialloDan/lab2/tree/v0.5.0)
- [v1.0.0](https://github.com/DialloDan/lab2/tree/v1.0.0)
- [v2.0.0](https://github.com/DialloDan/lab2/tree/v2.0.0)
