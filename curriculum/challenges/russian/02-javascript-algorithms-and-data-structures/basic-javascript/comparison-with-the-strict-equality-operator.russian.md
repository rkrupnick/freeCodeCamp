---
id: 56533eb9ac21ba0edf2244d1
title: Comparison with the Strict Equality Operator
challengeType: 1
videoUrl: ''
localeTitle: Сравнение с оператором строгого равенства
---

## Description
<section id="description"> Строгое равенство ( <code>===</code> ) является аналогом оператора равенства ( <code>==</code> ). Однако, в отличие от оператора равенства, который пытается преобразовать оба значения в общий тип, строгий оператор равенства не выполняет преобразование типа. Если сравниваемые значения имеют разные типы, они считаются неравными, а оператор строгого равенства возвращает false. <strong>Примеры</strong> <blockquote> 3 === 3 // true <br> 3 === &#39;3&#39; // false </blockquote> Во втором примере <code>3</code> является типом <code>Number</code> а <code>&#39;3&#39;</code> - <code>String</code> . </section>

## Instructions
<section id="instructions"> Используйте оператор строгого равенства в выражении <code>if</code> чтобы функция вернула «Равно», когда <code>val</code> строго равно <code>7</code> </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>testStrict(10)</code> должен вернуть «Не <code>testStrict(10)</code> »
    testString: 'assert(testStrict(10) === "Not Equal", "<code>testStrict(10)</code> should return "Not Equal"");'
  - text: <code>testStrict(7)</code> должен вернуть «Равный»
    testString: 'assert(testStrict(7) === "Equal", "<code>testStrict(7)</code> should return "Equal"");'
  - text: <code>testStrict(&quot;7&quot;)</code> должен возвращать &quot;Не равно&quot;
    testString: 'assert(testStrict("7") === "Not Equal", "<code>testStrict("7")</code> should return "Not Equal"");'
  - text: Вы должны использовать оператор <code>===</code>
    testString: 'assert(code.match(/(val\s*===\s*\d+)|(\d+\s*===\s*val)/g).length > 0, "You should use the <code>===</code> operator");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
// Setup
function testStrict(val) {
  if (val) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
