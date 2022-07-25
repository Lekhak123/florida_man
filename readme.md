
# Example

```js

const {fman} = require("./index.js");


async function f_man(month,date){
    let a = await fman(month,date);
    console.log(a)

}
f_man("march","1")
```
