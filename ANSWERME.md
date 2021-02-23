1. In the project there was a house that did not have a lord. Which house was this? And what did you do to deal with this situation?
   "House Stark of Winterfell" has no lord.
   With a condition I check the data.

2. You could have used XMLHttpRequest, the library axios or the fetch API to get the data from the server. And you could have used callbacks, async/await and/or promises. What did you use and why?
   (_TIP: There is no right way, all have their advantages and disadvantages. Explain your decision making listing the advantages/disadvantages of each technology/approach_)

I had to use async/await and fetch also promise.

3. Let's say you were a huge fan of Object Oriented Programming and you would have all the data the api provided in an array and you want to restructure your code in an OOP way. What classes would you make and what functions would they have?
   (_TIP: You do not have to write out the implementation of the functions (but you can if it makes it easier to think it through)_)
   (_TIP: If you are unsure between two decisions, then write a comment with the alternative you considered but decided against with arguments. There is again no one correct answer here, but we want to see you think in an OOP way_)
   (_TIP: If you want the code highlighting, it is also fine to create a `.js` file and then write down here what file to look at_)

   I created Dom class

Imagine the data is given as follows:

```
const data = [{
  name: 'Arryn',
  currentLord: 'https://example/',
  swornMembers: ['https://example/', 'https://example2']
}, {
  ...
}];
```

Example of how to write the classes (taken from <https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes>)

```
class Rectangle {
  constructor(height, width) {
    this.height = height;
    this.width = width;
  }

  get area() {
    // get the area of the rectangle
  }

  calcArea() {
    // calculate the area of the rectangle
  }
}
```
