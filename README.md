# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Olina Wong

Time spent: 1.5 hours spent in total

Link to project: https://troubled-morning-deposit.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] The buttons are all different shapes

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![x](https://i.imgur.com/L2UJfaB.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

When I opened the game in a new tab, it would work perfectly except it would not play the sounds when the buttons are pressed. I tried 
refreshing the page and looked over the code to see if there were errors anywhere. It was confusing because when I showed the window next 
to the code instead of in a new window, the sound would play. I resolved this error by opening it in another browser that was not Google
Chrome where it consistently worked. This meant that the error was not within my code but rather within the Google Chrome browser.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

Some questions I have include: 1) How would I be able to center titles and bodies of font on the page? 2) Is there a way I could display the 
end game message as a flash in the center of the screen as opposed to an alert? 3) Would there be a way to add a button that would change all 
of the red and green shades of color on the screen to a different color to allow for red green color blind users to more easily play the game? 
4) Why is there a rectangular outline around the buttons when I click on them? 5) What are ways web developers adjust web pages to be more 
accesible to a wider audience?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I worked on this project for a few more hours, I would add additional features. The optional features such as having the computer pick a new pattern and adding an image would be interesting to implement.
I would also likely see if I could write more functions and change the project to give the user the option to choose between lengths of patterns. For example, I would make three buttons instead of one start button
that would be easy, medium, and hard, and the user could choose the difficulty they would like. The difficulty would correspond to the length of the memory sequence, for example easy would be a 5 button pattern 
while hard could be a 15 button pattern. This would additionally allow the user to have different levels they can try and they could challenge themselves to be able to complete each level of difficulty. 
On the other hand, I would also be interested to spend time using the hidden feature to require the user to complete the easier modes before being able to move onto the more difficult modes. For example,
they would have to do easy before medium and medium before hard. This could be expanded to have more than three levels which would be a fun and challenging extension of the game.



## License

    Copyright Olina Wong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.