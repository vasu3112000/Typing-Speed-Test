# Typing Speed Tester

Typing speed means the number of words someone can accurately type in one minute. Thus, the unit being wpm(Words per minute). I've created this easy to use software which you can use to measure your typing speed.

## Installation

Download the complete folder and save it anywhere in your desktop. Open the file named test.py in a any python IDE such as pycharm, anaconda etc.

Install pygame, sys, time and random libraries in your interpreter if they are not present. Once installed, you're ready to use the software.

Once you run the code, a new window will open up and software launch picture will be displayed. Few seconds later, a new screen will come up displaying a text and a text box. You need to click in the text box and write the text displayed above. The code will match the text you wrote and the given text and also record the time you took to write that text.

Once you press enter, the code will display your typing speed underneath. To reload and practice more, click on the reset button available below.

## Code Explanation

The Game class created contains all the functions that will be used in our software to show the text, select the text from the file, count the total time you took and many more. 

The init function initializes the screen, the images, the accuracy, text etc. It declares and initializes all the variables and values that will be needed in our code further.

The draw_text function is used to render text messages on the screen. You need to input the screen where you want to display, message, font size and color of the font you want.

The show_result funcion will calculate your result of the test you gave and will display the result on the screen you gave in the input.

The run function is the main function of the code. It updates the text for user, displays the text box and shows the result of the user for the particular test.

The reset_game function displays works as per the name, it takes random sentences from the text file that I've given, draws heading, draws the rectangle box for input box and also displace the sentence string.

## Summary

As you might have understood till now, I've made a software that will help you test your typing speed and further improve it as per your performance. The sentences for testing purposes are displayed in sentence.txt file and thus, you can change them according to you wish. The code is written in a very easy manner so as to make it feasible for an unknown purpose to understand easily.
