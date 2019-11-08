# Обзор

В этом документе рассмотрим базовые операции JavaScript.

## 1. Вывод в отладочную консоль браузера

```js
console.log("Можно вывести любую строку");
console.log("Можно вывести одну строку", "Другую строку");
console.log("Можно вывести числа", 1, 2, 3);
```

## 2. Создание переменной с числовым значением

```js
var значение = 5;
console.log("Значение", значение);
```

## 3. Создание переменной со строковым значением

```js
var строка = "Содержимое строки";
console.log("Строка", строка);
```

## 4. Создание списка

```js
var элементы = [
    1,
    10,
    23
];
```

## 5. Получение длины списка (количества элементов списка)

```js
var длина = элементы.length;
console.log("Длина списка", длина);
```

## 6. Получение элемента списка по индексу

```js
var э = элементы[0];
console.log("Элемент списка", э);
```

## 7. Сравнение значения переменной с желаемым значением

```js
var число = 5;
if (число == 4)
{
    console.log("Число равно четырём");
}
else if (число == 5)
{
    console.log("Число равно пяти");
}
else
{
    console.log("Число не равно ни четырём, ни пяти", значение);
}
```

## 8. Сравнение нескольких значений

```js
var значение0 = элементы[0];
var значение1 = элементы[1];
if (значение0 == 5 && значение1 == 4)
{
    console.log("Значение0 равно пяти, а значение1 равно четырём");
}
```

## 9. Увеличение значения переменной

```js
var счётчик = 0;
счётчик += 1;
console.log(счётчик);
```