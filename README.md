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
