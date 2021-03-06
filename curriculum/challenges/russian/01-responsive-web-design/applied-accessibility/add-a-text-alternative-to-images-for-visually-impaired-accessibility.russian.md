---
id: 587d774c367417b2b2512a9c
title: Добавьте текстовое описание для изображений, чтобы увеличить их информативность для пользователей с нарушением зрения
challengeType: 0
videoUrl: ''
localeTitle: Добавьте текстовое описание для изображений, чтобы увеличить их информативность для пользователей с нарушением зрения
---
## Description (Описание)
<section id="description"> Вероятно, вы уже встречали атрибут <code>alt</code> в теге <code>img</code> в других задачах. <code>Alt</code> описывает содержимое изображения при помощи текстовой альтернативы. Текстовая альтернатива - тот текст, который увидит пользователь в том случае, если изображение не загружается, не может быть отображено, или пользователь с ограниченными возможностями не способен его увидеть. Поисковые системы также используют этот альтернативный текст в качестве описания изображения, чтобы включить изображение в результаты поиска. 
Например: <code>&lt;img src=&quot;importantLogo.jpeg&quot; alt=&quot;Company logo&quot;&gt;</code> 
Люди с нарушениями зрения полагаются на устройства чтения с экрана для преобразования веб-контента в аудиоинтерфейс. Они не могут получить информацию, которая представлена только в виде изображения, если это изображение не сопровождается описанием(текстовой альтернативой). Программы, предназначенные для людей с нарушениями зрения, могут получить доступ к атрибуту <code>alt</code> и прочитать его содержимое для доставки пользователю ключевой информации. Хорошее описание <code>alt</code> должно быть кратким, но достаточно емким, чтобы передать смысл изображения. Спецификация HTML5 требует обязательного включения атрибута <code>alt</code> для каждого изображения. </section>


## Instructions (Задание)
<section id="instructions"> Camper Cat, настоящий ниндзя в жизни и в программировании, создает веб-сайт, чтобы поделиться своими знаниями. Он хочет использовать изображение для профиля, которое продемонстрирует его навыки и будет оценено всеми посетителями сайта. Добавьте атрибут <code>alt</code> в тег <code>img</code> так, чтобы всем стало понятно, что Camper Cat занимается каратэ. (Изображение <code>src</code> не ссылается на фактический файл, поэтому вы должны увидеть текст <code>alt</code> на дисплее.) </section>
## Description
<section id="description"> Вероятно, вы видели атрибут <code>alt</code> в теге <code>img</code> в других задачах. Текст <code>Alt</code> описывает содержимое изображения и предоставляет текстовую альтернативу. Это помогает в случае, если изображение не загружается или не может быть замечено пользователем. Он также используется поисковыми системами, чтобы понять, что содержит изображение, чтобы включить его в результаты поиска. Вот пример: <code>&lt;img src=&quot;importantLogo.jpeg&quot; alt=&quot;Company logo&quot;&gt;</code> Люди с нарушениями зрения полагаются на устройства чтения с экрана для преобразования веб-контента в аудиоинтерфейс. Они не получат информацию, если они представлены только визуально. Для изображений экранные программы могут получить доступ к атрибуту <code>alt</code> и прочитать его содержимое для сообщения ключевой информации. Хороший <code>alt</code> представляет из себя короткий текст, который передает основной смысл изоражения. Вы всегда должны использовать атрибут <code>alt</code> для своих изображений. По спецификации HTML5 это считается обязательным. </section>

## Instructions
<section id="instructions"> Camper Cat оказался как ниндзя кодером, так и настоящим ниндзя, и создает веб-сайт, чтобы поделиться своими знаниями. Изображение профиля, которое он хочет использовать, показывает его навыки и должно быть оценено всеми посетителями сайта. Добавьте атрибут <code>alt</code> в тег <code>img</code> , который объясняет, что Camper Cat занимается каратэ. (Изображение <code>src</code> не ссылается на фактический файл, поэтому вы должны увидеть текст <code>alt</code> на дисплее.) </section>

## Tests (Тесты)

<section id='tests'>

```yml
tests:
  - text: 'Ваш тег <code>img</code> должен иметь атрибут <code>alt</code>, и он не должен быть пустым.'
    testString: 'assert($("img").attr("alt"), "Your <code>img</code> tag should have an <code>alt</code> attribute, and it should not be empty.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<img src="doingKarateWow.jpeg">

```

</div>



</section>

## Solution (Решение)
<section id='solution'>

```js
// здесь должно быть ваше решение
```
</section>
