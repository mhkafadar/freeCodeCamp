---
id: 587d7fb6367417b2b2512c09
title: Create and Save a Record of a Model
challengeType: 2
---

## Description
<section id='description'>
In this challenge you will have to create and save a record of a model.
</section>

## Instructions
<section id='instructions'>
Create a document instance using the <code>Person</code> constructor you built before. Pass to the constructor an object having the fields <code>name</code>, <code>age</code>, and <code>favoriteFoods</code>. Their types must be conformant to the ones in the Person Schema. Then call the method <code>document.save()</code> on the returned document instance. Pass to it a callback using the Node convention. This is a common pattern, all the following CRUD methods take a callback function like this as the last argument.
<blockquote>
/* Example */<br><br>
// ...<br>
person.save(function(err, data) {<br>
&nbsp;&nbsp;//   ...do your stuff here...<br>
});
</blockquote>
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Creating and saving a db item should succeed
    testString: 'getUserInput => $.get(getUserInput(''url'') + ''/_api/create-and-save-person'').then(data => { assert.isString(data.name, ''"item.name" should be a String''); assert.isNumber(data.age, ''28'', ''"item.age" should be a Number''); assert.isArray(data.favoriteFoods, ''"item.favoriteFoods" should be an Array''); assert.equal(data.__v, 0, ''The db item should be not previously edited''); }, xhr => { throw new Error(xhr.responseText); })'
```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```

</section>
