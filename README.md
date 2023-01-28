# CoreCode-Week-8-JavaScript-Introduction-

## Challenge 1 - if else operator

``` javascript
function saleHotdogs(n){
  if (n<5) {
    let price = n*100;
    return price; 
  }  else if (n>=5 && n<10){
    let price = n*95;
    return price; 
  } else
    {let price = n*90;
    return price; }
 ```

## Challenge 2 - switch operator

``` javascript
function howManydays(month){
  var days;
  switch (month){
    case 1:
      days = 31;
      break; 
      case 3:
      days = 31;
      break; 
      case 5:
      days = 31;
      break; 
      case 7:
      days = 31;
      break; case 8 :
      days = 31;
      break; 
      case 10:
      days = 31;
      break; 
      case 12:
      days = 31;
      break; 
    case 2: 
      days = 28;
      break; 
    case 4: 
      days = 30;
      break;
    case 6: 
      days = 30;
      break;
    case 9: 
      days = 30;
      break; 
    case 11: 
      days = 30;
      break;
  }
  return days;
}
```

## Challenge 3 - simple calculator

``` javascript
function calculate(num1, operation, num2) {
  switch (operation){
      case "+":
        var x = num1+num2;
        return x;
      break;
      case "-":
      var x = num1-num2;
        return x;
      break;
      case "/":
        if (num2 == 0){
          return null; 
        } else 
          return num1/num2;
      break;
      case "*":
        return num1*num2;
      break;
      default: 
        return null; 
        }
        }
 ``` 

## Challenge 4 - Odd or even

 ``` javascript
function evenOrOdd(number) {
  if (number % 2 == 0) {
    return "Even";
  } else 
    return "Odd";
}
 ```

## Challenge 5 - Wolves and Sheeps
Code War link
<https://www.codewars.com/kata/5c8bfa44b9d1192e1ebd3d15/train/javascript>

 ``` javascript
function warnTheSheep(queue) {
  for (let i = queue.length-1; i>=0; i--)  {
    let x = "wolf"
    if ((queue[queue.length-1] == x)|| (queue.length == 1)) {
        return "Pls go away and stop eating my sheep"
        } else
    if  (queue[i] == x) {
      return "Oi! Sheep number " + (queue.length - (i+1)) + "! You are about to be eaten by a wolf!" 
    } } }
```

## Challenge 6 - Morse Code
Code War Link 
<https://www.codewars.com/kata/54b724efac3d5402db00065e/train/javascript>

```javascript
decodeMorse = function(morseCode){
  let result = [];
  let palabra = morseCode.trim().split('   ');
  let letras = [];
  for (let i = 0; i < palabra.length ; i++){
    letras = palabra[i].split(' ');
    for (let p = 0; p<letras.length; p++){
      letras [p] = MORSE_CODE[letras[p]];
    }
    result.push(letras.join(''));
  }
  return result.join(' ').trim();
}
```

## Challenge 7 - Who likes it?
Code War Link
<https://www.codewars.com/kata/5266876b8f4bf2da9b000362/train/javascript>

``` javascript
function likes(names) {
  let n;
  if (names.length >= 4){
    n = names.slice(0,2);
    return `${n[0]}, ${n[1]} and ${names.length-2} others like this`
  } else 
    switch (names.length){
      case 3: 
    return `${names[0]}, ${names[1]} and ${names[2]} like this`
    case 2: 
    return `${names[0]} and ${names[1]} like this`
    case 1: 
    return `${names[0]} likes this`
    case 0: 
    return `no one likes this`
  }
}
```

## Challenge 8 - Bit counter
Code War Challenge 
<https://www.codewars.com/kata/526571aae218b8ee490006f4/train/javascript>
```javascript
var countBits = function(n) {
  let x = Math.abs(n);
  let binar = x.toString(2);
  let z = 0; 
  for (let i = 0; i<binar.length; i++){
    if (binar[i] === '1') z++
  }
  return z;
};
```


## Challenge 9 - Your order 
Codewar link
<https://www.codewars.com/kata/55c45be3b2079eccff00010f/train/javascript>

``` javascript
function order(words){
    let newWords = words.split(' ');
    let number = [];
    for (let i = 0; i<newWords.length+1; i++){
      for (let p = 0; p<newWords.length; p++){
        if (newWords[p].indexOf(i) >=0){
          number.push(newWords[p]); 
      }
        }
      }
  return number.join(' ')
  }
  ```
  
  ## Challenge 10 - 
