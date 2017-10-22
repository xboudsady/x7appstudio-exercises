### Problem 1 solution
```js
var firstNumber = prompt("Enter the first number", "");
    firstNumber = parseInt(firstNumber, 10);

var secondNumber = prompt("Enter the second number", "");
    secondNumber = parseInt(secondNumber, 10);

var theTotal = firstNumber + secondNumber;

document.write(firstNumber + " added to " + secondNumber + " equals " + theTotal);
```

Using the ``prompt()`` will return a string value of the represented number. 
```js
var theTotal = '5' + '5'    // '55'
```

You will need to use the `parse()` method to take the `prompt()` string value and return an integer.