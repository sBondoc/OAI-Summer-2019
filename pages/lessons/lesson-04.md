# Loops

One of the core strengths of using computer programs to solve problems is their ability to perform repetitive tasks in an interative manner. At the heart of this lies the use of loops, which enable you to repeat an action a certain amount of times without having to write down a line of code for each individual action.

### Exercises to accompany this lesson:

<ul>

<li><b><a href="https://studio.code.org/s/csp3-2019/stage/9/puzzle/1" target="_blank">Lesson 9: "Looping and Random Numbers"</a></b> <i>from <a href="https://studio.code.org/s/csp3-2019">AP Computer Science Principles Unit 3</a> at <a href="https://code.org">Code.org</a></i></li>

</ul>

## The purpose of loops

You've used functions to save on lines of code; if there are multiple places in your code where you want to perform an action 5 times, you can just make a function for it. But what if you want to do an action 10 times? 100? 1000?

Somewhere in your program, whether it be in a function definition or in the main code, there'd still have to be 1000 lines of code for you to write down. Even if copy/pasting the lines would make it relatively simple to do this, the amount of lines in the code would make the file size of the program larger than necessary.

Loops enable you to do just that. Instead of having the same line of code written down 1000 times, you can just specify in the beginning of the loop that the code within the loop is to be executed 1000 times.

Moreover, this has the added flexibility to be adaptable to changes that may happen in your program; the number of times the loop is repeated can be dynamic based on conditions set by the user, as will be elaborated later.

## Loop syntax

There are two main types of loops: `for` loops and `while` loops, the latter of which will be covered in a later lesson. The syntax of a `for` loop in JavaScript looks something like this:

```javascript
for (var i = 0; i < 5; i++) {
  // Your code here
}
```

Note the positioning of the start `{` and end `}` brackets. These denote the code that is considered "within" the loop and will be repeated.

The `5` between the `<` and `;` is how many times the loop will be repeated. For now, you may ignore the other parts (`for (var i = 0; i < ` and `; i++)`) of the loop and keep them the same for each loop you create. Just be mindful of where the brackets go.

If you're working with code blocks, AppLab actually only lets you modify the number that specifies the number of times the loop is to be repeated.

![00](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-04/00.gif "Only the repetition count for a loop can be modified in Applab code blocks.")

For future reference, the three terms `var i = 0`, `i < 5`, and `i++` describe the iteration variable, the termination condition, and the incremental statement for the loop, respectively. Variables and conditionals will be covered in later lessons.

## Using loops with function parameters

The repetition count in a `for` loop can be dynamically set to correspond with a function parameter, if the loop is within a function. For instance, if you wanted to create a turtle function that moved the turtle forward the default distance a certain number of times based on an input parameter, you could do something like this:

```javascript
function repeatForward(count) {
  for (var i = 0; i < count; i++) {
    moveForward();
  }
}
```

Calling `repeatForward()` with a parameter value of 5 would result in the following:

![01](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-04/01.gif "Our repeatForward() command in action")

You could even throw in some `turnLeft()` commands as well to get a sort of spiral going:

```javascript
repeatForward(1);
turnLeft();
repeatForward(1);
turnLeft();
repeatForward(2);
turnLeft();
repeatForward(2);
turnLeft();
repeatForward(3);
turnLeft();
repeatForward(3);
turnLeft();
```

Later on, you'll be able to simplify the above code even further using more complex looping techniques after we cover variables.

---

<div align="center"><a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-03.html"><b><<</b></a> | <a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-05.html"><b>>></b></a></div>
