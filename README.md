# homework-7

Создайте репозиторий homework-7 и добавьте файлы index.html и main.js.

## Задание

Написать функцию throughOnce, которая ограничивает вызов функции, переданной как аргумент, через раз.

Пример:
```js
function throughOnce(fn) {
  //...
}

var logThroughOnce = throughOnce(function(text) {
  console.log(text);
});

logThroughOnce("Hello World!"); // "Hello World!"
logThroughOnce("Hello World!"); //
logThroughOnce("Hello World!"); // "Hello World!"
logThroughOnce("Hello World!"); //
```
