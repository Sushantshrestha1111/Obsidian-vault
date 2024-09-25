always returns refrence to current object

```javascript
const person={
name:"sushant",
walk(){
console.log(this)
}
};

person.walk();
```