# prompt-and-alert

# Українська

## Встановлення

Введи у термінал (після встановлення `NodeJS`): 

```console
npm install prompt-and-alert
```

Постав у початок файлу:

```js
let alert = require('prompt-and-alert').alert;
let getChar = require('prompt-and-alert').getChar;
let readWord = require('prompt-and-alert').readWord;
let readLine = require('prompt-and-alert').readLine;
let prompt = require('prompt-and-alert').prompt;
```

## Функції

* **`alert(msg, true/false)`** — вивід у коноль
    
    `msg` — повідомлення, яке буде виводитися в консоль

    `true/false` — другий аргумент, від якого залежить чи буде ігноруватися закінчення рядка. (`true` – закінчення рядка перевірятися не буде, `false`(за замовченням) – до закінчення буде дописуватися `\n`, якщо його нема)

* **`getChar()`** — отримання char-коду останнього непрочитаного символа

* **`readWord(end)`** — читання останнього непрочитаного слова

    `end` — символи, які розділяють слова. За замовчуванням `" \r\n"`

* **`readLine(sep)`** — читання останнього непрочитаного рядка

    `sep` — символ, який розділяє слова в рядку, по ньому відбувається поділ рядка на масив слів. За замовченням `""` і ділення на масив слів не відбуваєтться

* **`prompt(msg)`** — читання з консолі після вивіду в консоль повідомлення

    `msg` — повідомлення, яке буде виводитися в консоль

# English

## Installation

Type to terminal (after installing `NodeJS`):

```console
npm install prompt-and-alert
```

Put on a start of a file:

```js
let alert = require('prompt-and-alert').alert;
let getChar = require('prompt-and-alert').getChar;
let readWord = require('prompt-and-alert').readWord;
let readLine = require('prompt-and-alert').readLine;
let prompt = require('prompt-and-alert').prompt;
```

## Functions

* **`alert(msg, true/false)`** — output to console
    
    `msg` — message, which will be outputed to console

    `true/false` — the second argument that determines whether the end of the line will be ignored. (`true` - the end of the line will not be checked,` false` (default) - the end will be added `\n` if it is not)

* **`getChar()`** — get char code of last unread symbol

* **`readWord(end)`** — reading last unread word

    `end` — characters that separate words. Default `" \r\n"`

* **`readLine(sep)`** — reading last unread line

    `sep` — a character that separates words in a line, it divides the line into an array of words. By default, `""` is not divided into an array of words

* **`prompt(msg)`** — reading from console after outputing message to console

    `msg` — message, which will be outputed to console

***

***v1.5.0***

***`(c)`*** **2022-05-18** *alkhizha*, *s0urce18*

***
