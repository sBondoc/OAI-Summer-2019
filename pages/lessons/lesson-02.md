# Functions

Functions are subroutines that can be called like commands. Essentially, making a function is like defining your own command that's made up of other commands. This helps keep things organized and can save time writing a certain sequence of commands that gets repeated throughout your code.

### Exercises to accompany this lesson:

<ul>

<li><b><a href="https://studio.code.org/s/csp3-2019/stage/5/puzzle/1" target="_blank">Lesson 5: "Creating Functions"</a></b> <i>from <a href="https://studio.code.org/s/csp3-2019">AP Computer Science Principles Unit 3</a> at <a href="https://code.org">Code.org</a></i></li>

<li><b><a href="https://studio.code.org/s/csp3-2019/stage/6/puzzle/1" target="_blank">Lesson 6: "Functions and Top-Down Design"</a></b> <i>from <a href="https://studio.code.org/s/csp3-2019">AP Computer Science Principles Unit 3</a> at <a href="https://code.org">Code.org</a></i></li>

</ul>

## Making functions

* Functions are written like any other instructions
* Code blocks show commands within the function as enclosed by the function block
* AppLab automatically indents text commands within function definition

Adding commands to a function is the same as adding commands to the main code. You can use code blocks...

![00](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-02/00.gif "Adding code blocks to function blocks.")

... or you can type text...

![01](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-02/01.gif "Adding text to function definitions.")

In virtually every coding language, indentation is used to keep thinks like function definitions organized (although in some cases indentation may not be required). This way it is easier to discern which commands are part of the function you're looking at.

## How functions work

* Commands within a function are executed from top to bottom
* AppLab jumps to the function definition and highlights accordingly when execution speed is lowered
* Functions can be called inside functions

You may remember using functions in Thunkable or MIT App Inventor.

![02](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-02/02.png "Thunkable function blocks.")

Something similar can be done in AppLab.

![03](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-02/03.png "AppLab function blocks.")

There is no function definition or command for `moveForward` or `turnLeft` in Thunkable, so it would result in an error if executed. However, even if they were defined, the code still wouldn't do anything. Niether would the above JavaScript. This is because both the Thunkable blocks and the JavaScript code lack a function call. That is, the function is defined, but it is not being executed. In Thunkable, there needs to be an event or trigger for anything to happen, and in the JavaScript above, there is nothing in the main code that calls for `main()` (a function, unused as indicated by the yellow warning symbol) or `myFunction()` to be executed.

In order for the JavaScript to do something in AppLab, you would have to call `myFunction()` or `main()` somewhere in the main code (outside of the function definition brackets).

```javascript
function main() {
  moveForward();
  moveForward();
  turnLeft();
  moveForward();
  moveForward();
  myFunction();
}

function myFunction() {
  turnLeft();
  turnLeft();
  turnLeft();
  moveForward();
}

main();
```

Notice that `main()` contains a call for `myFunction()` within its list of commands. That means while executing `main()`, `myFunction()` will execute after the commands before it within the function definition.

Also note the parentheses `()` at the end of the function definitions and calls. These are necessary and their purpose will be explained in the next lesson.

---

<div align="center"><a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-01.html"><b><<</b></a> | <a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-03.html"><b>>></b></a></div>
