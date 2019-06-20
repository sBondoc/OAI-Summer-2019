# Turtle programming

Programming using [Turtle graphics](https://en.wikipedia.org/wiki/Turtle_graphics) helps people get acquainted with the flow of programs. This lesson will focus on using turtle commands in AppLab to perform the tasks designated in the exercises.

### Exercises to accompany this lesson:

 <b><a href = "https://studio.code.org/s/csp3-2019/stage/4/puzzle/1" target = "_blank">Lesson 4: "Using Simple Commands"</a></b> _from [AP Computer Science Principles Unit 3](https://studio.code.org/s/csp3-2019) at [Code.org](https://code.org)_

## Commands

* Commands are basic instructions to be executed by the code
* Executed in order from top to bottom
* Turtle commands are meant to be easier to interpret

In AppLab, turtle commands are simplified so that there is an intuitive correlation between what the command does visually to the "turtle" (the arrow on the emulator) and its name. For example, the `moveForward()` command moves the turtle forward (i.e. changes its position to be a set distance away from its current position in the direction it is facing), and the `turnLeft()` command turns the turtle to the left (i.e. rotates it 90° counterclockwise).

In any coding language at their base level, commands are executed line by line from top to bottom. So, if you wanted your turtle to move forward 3 times, turn left, and then move forward 2 times, the code would look something like this in blocks...

![00](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/00.png "Block sample code.")

... or this in text...

```javascript
moveForward();
moveForward();
moveForward();
turnLeft();
moveForward();
moveForward();
```

Notice the semicolons (`;`) at the ends of the lines. These are necessary; don't forget to add them.

Executing this code should yield the following end result:

![01](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/01.png "Final display.")

## Coding in AppLab

* You can code using blocks or the text editor
* Toggling between the two views allows you to see what blocks look like in text form
* Beware of syntax in the text editor

Using code blocks is as simple as dragging and dropping the commands you wish to use into the workspace.

![02](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/02.gif "Adding block commands.")

You can also box select code blocks and copy/paste them using the [<kbd>ctrl</kbd>+<kbd>c</kbd>] and [<kbd>ctrl</kbd>+<kbd>v</kbd>] keyboard shortcuts.

![03](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/03.gif "Box selecting, copying, and pasting block commands.")

Blocks can be rearranged by clicking them and dragging them in the desired order. Dragging them outside of the workspace causes them to be removed from the program, and they can be box selected to remove multiple at a time.

![04](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/04.gif "Removing block commands.")

The controls on the text editor are the same as with any word-processing program (e.g. [Notepad](https://en.wikipedia.org/wiki/Microsoft_Notepad) or [Word](https://en.wikipedia.org/wiki/Microsoft_Word)). As you're typing, AppLab will also provide autofill suggestions for commands.

![05](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/05.gif "Typing commands.")

Copying and pasting content is the same as in other text editors, with the right-click functionality as well as the aforementioned [<kbd>ctrl</kbd>+<kbd>c</kbd>] and [<kbd>ctrl</kbd>+<kbd>v</kbd>] keyboard shortcuts.

![06](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/06.gif "Copy/pasting in text editor.")

Getting rid of text commands is also the same.

![07](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/07.gif "Removing text commands.")

Another feature of AppLab is that dragging and dropping block commands from the toolbox in text mode pastes the corresponding text into the editor.

![08](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/08.gif "Dragging blocks into text.")

## Debugging in AppLab

* "Debugging" is essentially fixing your code
* You can change the speed at which the lines of code are executed
* Slowing down the execution allows you to see what the turtle does step-by-step

By default, lines of code are executed almost instantaneously. However, it may help to see the program as it's executing, rather than just the end result, especially if something went wrong along the way and what you end up with isn't what you'd hoped for.

AppLab has a slider under the workspace that allows you to change the execution speed of the code.

![09](https://raw.githubusercontent.com/sBondoc/OAI-Summer-2019/master/assets/lesson-01/09.png "Speed slider.")

When doing turtle programming, this allows you to see the actions of the turtle that you'd otherwise be unable to see with near-instantaneous execution of the code. Moreover, AppLab highlights each line of code as they are run when the execution speed is not set to instantaneous (with the slider all the way to the right).

![10]("Line-by-line highlighting and execution.")

More details on debug tools available in AppLab will be covered at a later time.

## Comparison with MIT App Inventor


---

<div style="text-align: right"><a href = "https://sbondoc.github.io/OAI-Summer-2019/pages/lessons/lesson-01.html"><i><b>Continue to next lesson...
