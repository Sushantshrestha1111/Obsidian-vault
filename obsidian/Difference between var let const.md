```javascript
//var function scoped hunxa =>

function abcd(){
for (var i=1;i=12;i++){
console.log(i);
}
console.log(i);
}

//if var is declared inside function it can be used anywhere inside a function

result will be 1-12

//let is brace scoped 
function abcd(){
for (var i=1;i=12;i++){
console.log(i);
}
console.log(i);
}
//in this it will not allow i to use outside for
result will be 1-11 and then error


//var adds itself to the window object

```