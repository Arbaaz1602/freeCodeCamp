---
title: Remove Whitespace from Start and End
localeTitle: Удаление пробелов от начала и конца
---
## Удаление пробелов от начала и конца

Чтобы решить эту задачу, вам просто нужно создать строку регулярного выражения, которая соответствует любым пробелам в начале или в конце строки.

## Подсказка 1:

Подумайте, как вы можете выбрать подстроки в начале или конце строки.

## Подсказка 2:

Подумайте, как вы можете выбрать пробелы

## Оповещение о спойлере - решение впереди!

## Решение:

```javascript
let hello = "   Hello, World!  "; 
 let wsRegex = /^\s+|\s+$/g; // Change this line 
 let result = hello.replace(wsRegex, ''); // Change this line 

```