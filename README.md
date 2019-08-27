# able-test
### Description
This repository presents a simple problem to be solved by new ABLE candidates that want to contribute
to the ABLE project. Even though it has been specifically designed for this purpose, it has common
aspects with work being currently done in the ABLE desktop application. Apart from being a coding problem,
this exercise will be evaluated from other perspectives such as code cleanliness, code structure, 
code documentation, git flow, ...
### The problem
Using PyQt5, the user should create a simple window with a pushbutton in the middle.
When this pushbutton is pressed, a popup window should open prompting the user on whether they want
to close the application or not. The same popup window should open when the Windows close button or 
Alt+F4 are pressed. These are the basic functionalities the app should have. If the candidate feels
like going further, some extra features have also been listed.
### System requirements
* Windows machine
* [Python 3.x](https://www.python.org/) installed
* [PyQt5](https://pypi.org/project/PyQt5/) installed

### What will be evaluated
* **The functionality and performance of the code:** The code should work and no unexpected behaviour
should occur. This means, no sudden crashes regardless of how the user interacts with the app.
* **Cleanliness of the code:** the code should be well structured and it should be understandable by 
the evaluators. For us, it is better to write some extra lines or longer variable names if this let's 
another developer contribute easier and faster. 
* **Scalability of the architecture:** even though the exercise may seem simple, it should be resolved as it was
the first step of a much bigger project, considering other developers will contribute in the future. 
In this way, MVC architectures are highly welcomed.
* **Documentation:** the code should be well documented following any of the documentation standards
for Python.
* **The procedures followed to contribute in the git repository:** [this link](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/)
perfectly describes what would be a clean contribution to an external repository. The contributing branch
should be **branched from develop**.
### Basic functionalities
1. A simple window like the following should be created at startup:

![Alt text](/media/basic_layout.PNG "Basic Layout")
- Background in color #2a2a2a (RGB: 42, 42, 42). Button color #535353 (RGB: 83, 83, 83)
- Button should be centered in window
- Button size 100x100. Text in white, font size 16 px, bold.
- Main Window size at creation: 200x200. Mimimum size possible: 200x200
- When button is pressed, popup message should be shown as image. The same popup should appear if trying to close application from top bar cross button. Default answer when enter is pressed should be cancel.
#### Extra features
- Show ABLE icon in both the top bar and the task bar
- Replace the button by a exit button6 and make it responsive to hover and press.
- Button should be recentered every time the window resizes.
- Top bar icon of popup message ABLE icon
- Popup message icon (information), replaced by exit button
- Change cursor to pointing hand when hovering button
