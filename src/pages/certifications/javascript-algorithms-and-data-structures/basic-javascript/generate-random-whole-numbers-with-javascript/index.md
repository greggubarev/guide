
## Generate Random Whole Numbers with JavaScript

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->
This is our setup:

```javascript
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.

 return Math.random();
}
```

We need to use ```Math.random()``` function with ```Math.floor()``` function, for generate and return a random whole number between 0 and 9. 
After ```// Only change code below this line.``` line, we add our functions:

```javascript
  Math.floor(Math.random() *10);
  ```
and we need to change 
  
```javascript
  return Math.random();
  ```
  
 to 
 
  ```javascript
  Math.floor(Math.random());
  ```
so that the function returns to us the result of our calculations.

Here’s a full solution:

```javascript
var randomNumberBetween0and19 = Math.floor(Math.random() * 20);

function randomWholeNum() {

  // Only change code below this line.
  
  Math.floor(Math.random() *10);
  return Math.floor(Math.random());
}
```
