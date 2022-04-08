# Class 5: 

### Example of for loop from warm up
- Create a function that uses 2 paramenters, the first parameter is an array of numbers, the first parameter is an array of numbers, and the second is a single integer number. 
- The function returns that same array, but adds that second parameter to each number within the array. 

## JS TO STUDY: parameters, arrays, return, if(), for(), console.log, push, function vs property, method, object
- the function typeof returns string data, which can be a number still or other data types, and then it returns the data back in a string form.
- use break for ending loops, return stops running the function and gets out to the bigger function

```javascript

var arrayOfNumbers = [1, 10, 15, 20]
var number = 5;

// parameters: variables that we define within the paranthesis of the functions signature or declare 
//parameter 1 is an array of integers
//parameter 2 is an integer
function sumThisUp(arrayThatWeWantToAddTo, numberWeWantToAddTo){

//If this 
  if (typeof(arrayThatWeWantToAddTo) !== 'number'){
    console.log('Please give me an integer as parameter 2');
    return;
  }

  for(var i = 0; i < arrayWeWantToAddTo.length; i++){
    console.log(arrayThatWeWantToAddTo[i] + numberWeWantToAdd);
    results.push(arrayThatWeWantToAddTo[i])
  }
  return results;
}
//we call (aka invoke) the function here
var newArray = sumThisUp([1,10,15,20], 5)
```

## Javascript Fundamentals
```javascript
'var nums = new Array(10).fill('');' => 'var nums = ['','','','','','','','','','']'
```

## CSS
```css
input[type='text'] {
  background-color: red;
}

div:hover {
  background-color: pink;
}

```
CSS to try- 
- img 
  - overflow:
  - background-image: url("URLHERE")
-font-family: 
- font-weight: (makes the letters heavier, kind of bolding)
-caniuse.com to see what browsers support what I'm using
- rgb (0,0,255) all black. 

### *CSS to google*
- "font styles" ie serif, cursive, etc
- Google Fonts
- 
