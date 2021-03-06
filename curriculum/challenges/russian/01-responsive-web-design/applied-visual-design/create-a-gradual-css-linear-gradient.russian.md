---
id: 587d78a5367417b2b2512ad6
title: Create a Gradual CSS Linear Gradient
challengeType: 0
videoUrl: ''
localeTitle: Создать линейный градиент линейного CSS
---

## Description
<section id="description"> Применение цвета на элементах HTML не ограничивается одним плоским оттенком. CSS обеспечивает возможность использования цветовых переходов, иначе называемых градиентами, на элементах. Доступ к нему осуществляется через <code>background</code> отеля <code>linear-gradient()</code> функции. Вот общий синтаксис: <code>background: linear-gradient(gradient_direction, color 1, color 2, color 3, ...);</code> Первый аргумент указывает направление, с которого начинается переход цвета - его можно указать как градус, где 90deg делает вертикальный градиент, а 45deg - угловым, как обратная косая черта. Следующие аргументы определяют порядок цветов, используемых в градиенте. Пример: <code>background: linear-gradient(90deg, red, yellow, rgb(204, 204, 255));</code> </section>

## Instructions
<section id="instructions"> Используйте <code>linear-gradient()</code> для <code>background</code> элемента <code>div</code> и установите его в направлении 35 градусов, чтобы изменить цвет с <code>#CCFFFF</code> на <code>#FFCCCC</code> . <strong>Заметка</strong> <br> Хотя есть другие способы указать значение цвета, например <code>rgb()</code> или <code>hsl()</code> , используйте шестнадцатеричные значения для этой задачи. </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Элемент <code>div</code> должен иметь <code>background</code> с <code>linear-gradient</code> с заданным направлением и цветами.
    testString: 'assert(code.match(/background:\s*?linear-gradient\(35deg,\s*?(#CCFFFF|#CFF),\s*?(#FFCCCC|#FCC)\);/gi), "The <code>div</code> element should have a <code>linear-gradient</code> <code>background</code> with the specified direction and colors.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<style>

  div{
    border-radius: 20px;
    width: 70%;
    height: 400px;
    margin: 50px auto;

  }

</style>

<div></div>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
