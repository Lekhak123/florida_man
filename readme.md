```
npm i florida_man
```
to compile to js:
```
npx tsc index.ts
```

# Example

```js

const {fman} = require("florida_man");


async function f_man(month,date){
    let a = await fman(month,date);
    console.log(a)

}
f_man("march","1")
```
