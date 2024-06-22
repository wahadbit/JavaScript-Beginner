# Введение

В этом уроке мы рассмотрим примитивные типы данных в JavaScript. Примитивные типы данных — это основные строительные блоки языка, которые позволяют работать с различными видами информации. Понимание этих типов данных является фундаментальным для эффективного программирования на JavaScript.

# Числа (number)

Числовой тип данных `number` используется для представления как целых, так и дробных чисел. В JavaScript нет отдельных типов для целых и дробных чисел — все они относятся к типу `number`.

**Примеры чисел:**

```
let integer = 42;
let float = 3.14;
```

**Особенности:**
- Операции с числами: Вы можете выполнять различные арифметические операции с числами, такие как сложение, вычитание, умножение и деление.
- `NaN`: Специальное значение `NaN` (Not a Number) появляется, если операция с числами невозможна.

```
let result = 0 / 0; // NaN
```

# Строки (string)

Строки `string` используются для представления текста. Строки в JavaScript могут быть заключены в одинарные кавычки (`'`), двойные кавычки (`"`) или косые кавычки (` ` `).

**Примеры строк:**

```
let singleQuoteString = 'Hello, world!';
let doubleQuoteString = "Hello, world!";
let templateString = `Hello, world!`;
```

**Особенности:**
- Конкатенация строк: Вы можете объединять строки с помощью оператора `+`.

```
let greeting = 'Hello, ' + 'world!'; // "Hello, world!"
```