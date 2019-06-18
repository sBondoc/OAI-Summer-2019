# Intro to AppLab

AppLab is a tool similar to MIT App Inventor and Thunkable that is intended for use as an introductory platform for app development.

## Transitioning to new platforms

* Code blocks aren't used in real-world programs
* The're an introductory tool

Basically, this...

![01](https://raw.githubusercontent.com/sBondoc/oai_2019/master/assets/lesson-00/00.png "I guess it looks colorful...")

... just looks a little nicer than this...

![02](https://raw.githubusercontent.com/sBondoc/oai_2019/master/assets/lesson-00/01.png "Ahhh!")

Granted, the former and the latter do not represent codes that perform the same task, but the idea remains the same: code blocks are a more user-friendly visual aid.

## Coding Languages

* You can write programs that do the same thing in different ways
* Coding languages are like tools; each one is better suited for certain tasks than others

You can have a program display the numbers 1-10 on new lines...

![03](https://github.com/sBondoc/oai_2019/blob/master/assets/lesson-00/03.png?raw=true "Console text.")

... using Python...

```python

def main():
	print("Hello world!\nHere are the numbers 1-10:")
	for i in range(10):
		print(i)

```

... or C...

```c

#include <stdio.h>

int main() {
	printf("Hello world!\nHere are the numbers 1-10:");
	for (int i = 1; i < 11; i++) {
		printf("\n%d", i);
	}

	return 0;
}

```

... or JavaScript...

```javascript

function main() {
	console.log("Hello world!");
	console.log("Here are the numbers 1-10:");
	for (var i = 1; i < 11; i++) {
		console.log(i) 
	}
}

```

... or in pretty much any other coding language. Most Andraid apps are written in [Java](https://en.wikipedia.org/wiki/Java_(programming_language)), whereas most iOS apps use [Swift](https://en.wikipedia.org/wiki/Swift_(programming_language)).

## AppLab

AppLab 
