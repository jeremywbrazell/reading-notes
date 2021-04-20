**1. Describe (in plain English) what Array.map() does.**
This creates a new array from an existing one by looping through the original array, changing it, then pushing it into a new one.

**1. Describe (in plain English) what Array.reduce() does**
This reduces an array to a single value, which can be a number, string, object, or even a new array.  It accepts two arguments: the accumulator(current combined value) and the current(item in the loop).

**1. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result**
**- With normal Promise .then() syntax**
```
const getURL = superagent
.get(url).query(query)
.then(results => {
	const shoes = results.body.data;
	const finalShoes = shoes.map(item => {
return new Shoe(item);
   });
});
```

**- Again with async / await syntax**
```
const superagent = require('superagent');

const retries = 3;

test();

async function test() {
  let i;
  for (i = 0; i < retries; ++i) {
    try {
      await superagent.get('http://google.com/this-throws-an-error');
      break;
    } catch(err) {}
  }
  console.log(i); // 3
}
```

**Explain promises as though you were mentoring a Code 301 level student.**
A promise is an object that potentially could create a single value in the future, which would indicate something resolved or unresolved, like an error.

**Are all callback functions considered to be Asynchronous? Why or Why Not?**
Yes and no.  Every asyncrhonous function takes a function argument, but not every function that does so is asyncronous and it depends on how the function is used inside the argument.