---
id: 694892bf-a386-4b71-a6ea-745bfc1338e2
title: Переменные в JavaScript
slug: variables
summary: 'Изучаем let, const и var.'
status: published
position: 11
estimatedReadMinutes: 8
---

# Переменные в JavaScript

Переменная позволяет сохранить значение
для дальнейшего использования в программе.

## Объявление переменных

В современном JavaScript чаще используют
`let` и `const`.

```javascript
const name = "Alex";
let age = 25;

age = 26;

console.log(name, age);
```

## Разница между let и const

`let` позволяет повторно присваивать значение.

`const` запрещает повторное присваивание.

При этом `const` не делает содержимое объекта
неизменяемым.
