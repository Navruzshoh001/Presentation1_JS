# Presentation1_JS

# Java Script LECTURE 1

## Начало работы с Javascript.

>JavaScript — популярное программирование язык.
>
>Ранее JavaScript использовался в основном для создание интерактивных веб-страниц, таких как форма валидация, анимация и т. д. В настоящее время JavaScript также используется во многих других областях такие как серверная разработка, мобильная разработка приложений и так далее.

## JavaScript также используется во многих других областях.

>JavaScript - это популярный язык программирования, который имеет широкий спектр применения. В рейтинге stackoverflow (один из самых популярных сайтов для программистов) javascript занимает первое место. В рейтинге github (тоже один из самых популярных сайтов для программистов) занимает второе место.

## РОЛЬ JAVASCRIPT В ВЕБ-РАЗРАБОТКЕ.

>JavaScript это язык, который позволяет вам применять сложные вещи на web странице — каждый раз, когда на web странице происходит что-то большее, чем просто её статичное отображение — отображение периодически обновляемого контента, или интерактивных карт, или анимация 2D/3D графики, или прокрутка видео в проигрывателе, и т.д. — можете быть уверены, что скорее всего, не обошлось без JavaScript. Это третий слой слоёного пирога стандартных web технологий, два из которых (HTML и CSS) мы детально раскрыли в других частях учебного пособия.
>
>![](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_is_JavaScript/cake.png)

## КРАТКАЯ ИСТОРИЯ JAVASCRIPT.

> Впервые JavaScript построили в 1995 году. Первые 10 дней его название было Mocha и LiveScript. Потом в 1996 году его переименовали в JavaScript. Каждый год в JavaScript добавляют новые обновлении под названии ECMA Script(ES1). Самая большая обновления было в 2015 году.

## Запустить JavaScript

>Вы можете запускать JavaScript 3 способами:
> - 1)Node.js
> - 2)Использование вкладки console веб-браузеров
> - 3)Создавая веб-страницы

## Переменные и константы JavaScript

>Для хранения данных в программе используются переменные. Переменные предназначены для хранения каких-нибудь временных данных или таких данных, которые в процессе работы могут менять свое значение.
>
>CONST - создаёт константу (новую именованную ссылку на область памяти), доступную только для чтения. Это не означает, что указываемое значение неизменно, но это означает, что идентификатор не может быть переназначен. Например, если константа указывает на объект, то сам объект может быть изменён.
>
>Оператор VAR служит для объявления переменных. Типы переменных в языке JavaScript не объявляются очевидно, тем не менее они присутствуют. Интерпретатор понимает что записывается в переменную и на основании этого добавляет тип к этой переменной.
>
>Директива LET позволяет объявить локальную переменную с областью видимости, ограниченной текущим блоком кода . В отличие от ключевого слова var (en-US), которое объявляет переменную глобально или локально во всей функции, независимо от области блока.

## ОБЪЕКТЫ И ПРИМИТИВЫ.

>Объекты (в том числе и массивы, как вы уже знаете) считаются сложными типами данных. Строки, числа, логические значения считаются простыми, или примитивными типами данных. Их часто так и называют - примитивы, подразумевая все то, что не является объектом.
>
>В JavaScript семь примитивных типов данных: string, number, boolean, null, undefined, symbol, bigint. Запомните их количество и названия - это часто спрашивают на собеседованиях.
>
>![](https://www.javascripttutorial.net/wp-content/uploads/2022/01/JavaScript-data-types.svg)

## Правила именования переменных JavaScript

>Имена переменных должны начинаться либо с буквы, либо с символа подчеркивания _, либо со знака доллара $.

## Операторы В JavaScript

>![](https://storage.yandexcloud.net/wr4img/272458_134__143.png_0)

## Арифметические операторы JavaScript

>![](http://bookhtml.ru/images/stories/tabl14.2.jpg)

##  ЛОГИЧЕСКИЕ ОПЕРАТОРЫ: И(&&), ИЛИ( | | ), НЕ(!)

>![](https://www.examtray.com/sites/default/files/styles/wordpress_800x460/public/2019-06/java-boolean-logical-operators-priotiry-table.jpg?itok=jcXIvptd)

# Table of Contents

> - 1)CONDITIONS
>
> - 2)LOOPS
>
> - 3)FUNCTIONS

## CONDITION Ternary operator

>![](https://static.javatpoint.com/core/images/ternary-operator-in-java3.png)

## FUNCTIONS

>A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output.
>
> - 1)Function declarations
>
> - 2)Function expressions = 1.Anonymous 2.Arrow
>
> - 3)Immidiatly Invoked Function Expression(IIFE)
>
>![](https://www.scientecheasy.com/wp-content/uploads/2022/02/javascript-function-syntax.png)

### FUNCTION Declaration

> The function declaration defines a function with the specified parameters.
>
> - A function is declared using the function keyword.
>
> - The basic rules of naming a function are similar to naming a variable. It is better to write a descriptive name for your function. For example, if a function is used to add two numbers, you could name the function add or addNumbers.

### FUNCTION expression

>A function expression is very similar to and has almost the same syntax as a function declaration. The main difference between a function expressionand a function declaration is the function name, which can be omitted in function expressions to create anonymous and arrow functions.


### FUNCTION iife

>An IIFE (Immediately Invoked  Function Expression) is a function that runs the moment it is invoked or called in the JavaScript event loop. Having a function that behaves that way can be useful in certain situations. IIFEs prevent pollution of the global JS scope.
>![](https://www.google.com/imgres?imgurl=https%3A%2F%2Fsarifulislam.com%2Fwp-content%2Fuploads%2F2018%2F10%2Fiife2.png&tbnid=RwpJ0HaNUzkqbM&vet=12ahUKEwjJv_H1i8D_AhVEh_0HHfz4DXgQMygBegUIARCtAQ..i&imgrefurl=https%3A%2F%2Fsarifulislam.com%2Fjavascript-iife%2F&docid=N8RJQirOoHj1MM&w=3000&h=1376&q=function%20IIFE&hl=ru&ved=2ahUKEwjJv_H1i8D_AhVEh_0HHfz4DXgQMygBegUIARCtAQ)

<!-- Adres ssilki -->
>![](https://www.google.com/imgres?imgurl=https%3A%2F%2Flookaside.fbsbx.com%2Flookaside%2Fcrawler%2Fmedia%2F%3Fmedia_id%3D100077692357186&tbnid=qfQW5XEyjqRBhM&vet=12ahUKEwiFv9-Ri8D_AhWogv0HHcdWCPwQMygAegUIARCuAQ..i&imgrefurl=https%3A%2F%2Fwww.facebook.com%2Finfosoftclub.tj%2F&docid=i1dHLmWF9hBe7M&w=1160&h=1160&q=softclub&ved=2ahUKEwiFv9-Ri8D_AhWogv0HHcdWCPwQMygAegUIARCuAQ)
