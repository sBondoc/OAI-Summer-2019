# Parameters

Functions are used for a lot more than just saving time writing repeated code. Sometimes you want a function to do something slightly different depending on the situation in which it's implemented. Functions can use parameters to perform certain tasks using different inputs.

### Exercises to accompany this lesson:

<ul>

<li><b><a href="https://studio.code.org/s/csp3-2019/stage/7/puzzle/1" target="_blank">Lesson 7: "APIs and Function Parameters"</a></b> <i>from <a href="https://studio.code.org/s/csp3-2019">AP Computer Science Principles Unit 3</a> at <a href="https://code.org">Code.org</a></i></li>

<li><b><a href="https://studio.code.org/s/csp3-2019/stage/8/puzzle/1" target="_blank">Lesson 8: "Creating Functions with Parameters"</a></b> <i>from <a href="https://studio.code.org/s/csp3-2019">AP Computer Science Principles Unit 3</a> at <a href="https://code.org">Code.org</a></i></li>

</ul>

## Adding new parameters to function definitions and function calls

* Parameters for a function are declared within the parentheses `()` of the function after the name
* In block view, parameters are added using the arrows on the function block
* Each parameter is separated by a comma `,`

The parentheses `()` that you've been adding at the end of each function and command (e.g. `moveForward`, `turnLeft`) are where parameters are supposed to go, so technically, you've been using turtle "commands" as parameterless functions.

In a function definition, you define a parameter by adding a name for it inside those parentheses. If you'd like to have multiple parameter definitions, you separate them with a comma `,`:

```javascript
function myFunction(myParameter1, myParameter2) {

}
```

In AppLab, you can use add a new parameter definition to a function declaration in block view by clicking the right arrow ![00](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-03/00.png) at the top of the block, while clicking the left arrow ![01](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-03/01.png) removes the last parameter definition in the top of the block:

![02](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-03/02.gif "Adding and removing parameters in block view.")

For function calls, instead of typing parameter names within the parentheses, you input values that can be referenced under the name of the parameter as defined in the function declaration:

```javascript
myFunction(3,7);
```

The process for inputting parameter values for a function call in block view is the same as when adding parameter definitions to the function declaration:

![03](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-03/03.gif "Adding and removing parameter values in block view.")

Keep in mind that function definitions are where you put the parameter name itself, and function calls are where you input values for those parameters.

## Using parameters in functions

* Parameters slightly change the way the function works
* When creating a function, it's typically built around the parameters
* Values in function calls correspond with parameters in the respective function definition in sequential order

Adding parameters to functions allows them to be more versatile, keeping the code shorter and easier to read. Making the comparison to math, a function will take an input and yield an output based on the function. It's the same with functions in coding.

Consider the `moveForward` turtle function. So far, you've only been able to move it forward one "space," a more or less discrete amount. So, if you wanted to move the turtle forward 5 spaces, you'd have to call `moveForward()` 5 times:

![04](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-03/04.gif "Moving forward without parameters.")

However, this doesn't allow you to move forward a fraction of a space. This is where parameters come in. The `moveForward()` function actually has a distance parameter, and up until now, you haven't been inputting a value for it, so it's been moving the default distance (25 pixels). By using the parameter in the `moveForward` function, you can now move the turtle forward in smaller increments:

```javascript
moveForward(5);
```

Not only that, we can complete the aforementioned step of moving forward the turtle an equivalent of 5 spaces (25 pixels per space) in a single line:

```javascript
moveForward(125);
```

Sometimes a function will have multiple parameters. Say you wanted to make a function called `moveForwardAndTurnLeft()`

---

<div align="center"><a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-02.html"><b><<</b></a> | <a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-04.html"><b>>></b></a></div>
