### Tips

```javascript
const args = process.argv;
console.log(args);
newArray = args.slice(2);
```
Use the slice method arrayname.slice(2) will slice the first 2 array that is displaying node and the file.

```terminal
> node sum.js 10 25 
[ 'node', //cuts this
'/focal/sum.js', //and this
'10',
'25' ]
```
```javascript
newArray[0] === '10'
```
Currently it's a string so we must use Number() function to convert into a number.

```javascript
console.log(Number(newArray[0])+(Number(newArray[1]))); /*adds the 2 numbers and converts string to number*/
```
