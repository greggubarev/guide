## Use Multiple Conditional (Ternary) Operators

<!-- The article goes here, in GitHub-flavored Markdown. Feel free to add YouTube videos, images, and CodePen/JSBin embeds  -->

We need to use multiple ```conditional operators``` in the ```checkSign``` function to check if a number is positive, negative or zero.

This is solution:

```javascript
function checkSign(num) {
  return (num === 10) ? "positive" : (num === -12) ? "negative" : "zero";
}

checkSign(10);
```
