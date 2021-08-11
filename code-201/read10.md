# **JS Debugging**
![img](https://image.slidesharecdn.com/debugging-javascript-web-141030080414-conversion-gate02/95/debugging-javascript-1-638.jpg?cb=1415345877)

## **What is debugging in JS?**
The debugger statement stops the execution of JavaScript, and calls (if available) the debugging function. Using the debugger statement has the same function as setting a breakpoint in the code. Normally, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

## **How do i debug in JS?**

> Step 1: Reproduce the bug

> Step 2: Get familiar with the Sources panel UI

> Step 3: Pause the code with a breakpoint

> Step 4: Step through the code


> Step 5: Set a line-of-code breakpoint


> Step 6: Check variable values


> Step 7: Apply a fix
___

## **JS Debugger**
Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.

Built-in debuggers can be turned on and off, forcing errors to be reported to the user.

With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.

Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

* ### **The console.log() Method**

If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window.

* ### **Setting Breakpoints**

In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).

* ### **The debugger Keyword**

The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function.

This has the same function as setting a breakpoint in the debugger.

If no debugging is available, the debugger statement has no effect.

With the debugger turned on, this code will stop executing before it executes the third line.
___

## **Major Browsers' Debugging Tools**

Normally, you activate debugging in your browser with F12, and select "Console" in the debugger menu.

Otherwise follow these steps:

> **Chrome**

* Open the browser.
* From the menu, select "More tools".
* From tools, choose "Developer tools".
* Finally, select Console.


> **Firefox**

* Open the browser.
* From the menu, select "Web Developer".
* Finally, select "Web Console".

> **Edge**

* Open the browser.
* From the menu, select "Developer Tools".
* Finally, select "Console".

> **Opera**

* Open the browser.
* From the menu, select "Developer".
* From "Developer", select "Developer tools".
* Finally, select "Console".

> **Safari**

* Go to Safari, Preferences, Advanced in the main menu.
* Check "Enable Show Develop menu in menu bar".
* When the new option "Develop" appears in the menu:
Choose "Show Error Console".