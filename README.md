# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nahom Agize**

Time spent: **5** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

## Required Functionality

The following **required** functionality is complete:

* [✓] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [✓] "Start" button toggles between "Start" and "Stop" when clicked. 
* [✓] Game buttons each light up and play a sound when clicked. 
* [✓] Computer plays back sequence of clues including sound and visual cue for each button
* [✓] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [✓] User wins the game after guessing a complete pattern
* [✓] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [✓] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [✓] Buttons use a pitch (frequency) other than the ones in the tutorial
* [✓] More than 4 functional game buttons
* [✓] Playback speeds up on each turn
* [✓] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [x] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/ds6GCGP1T3.gif)
![](http://g.recordit.co/vTYWi8oyYO.gif)
![](http://g.recordit.co/YfCVPt1v1i.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

Stackoverflow - To help with the randomization/shuffling of the starting pattern.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

Although not directly related to the content of this submission, a challenge I faced was allocating time for completing the submission. I planned to overload on my academic courses this semester, and thus the huge chunks of assignments barely gave me time to focus of my professional development. On the positive side, my career coach had informed me about this opportunity early in the month which provided me with enough time to plan ahead.  By managing my time properly and submitting my schoolwork before the due date, I was able to make time these past few days for working on my code path application. Specific to this code submission, I was faced with little-to-none challenge mainly due to the clarity of the guide on how to exactly implement the code for the desired game. Perhaps a small obstacle I faced was while implementing the optional feature for speeding up the playback on each turn. As instructed, I had changed the ‘clueHoldTime’ from constant to a variable and updated it in the ‘playClueSequence()’ function. As I was playing the game, the ‘clueHoldTime’ kept getting smaller even after starting the game again. Then I noticed the ‘clueHoldTime’ needs to be reset each time the player starts the game, so I put the line of code to reset the variable in the function ‘StartGame()’  but before the ‘playClueSequence()’ function.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing my submission, my main question would be: what are the best resources to use as a template for writing the lines of code in web development and how to get familiar with them? I have come across bootstrap4 from W3schools, and it has aided me quite a few times in my projects. Seeing how this guide was very straightforward and provided exactly what was needed to create the game, I came to wonder if there are such guides designed for different types of games and web applications. I assume spending a significant amount of time in such environment will help master key skills in being able to create desired web apps. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours, I would spend time replacing the square buttons with pictorial representations and readjusting the sounds generated when clicking on each corresponding image. Implementing these additional features would allow me to create a story line easy to follow and memorize in addition to making the game more interesting. Allowing for different randomized storylines to exist would require more time to come up with but will increase users’ engagement, especially if designed for kids. Perhaps it needs more than few hours but creating themes to choose from in creating the storylines would also be interesting. For instance, there would be one theme in relation to farm animals (with associated sounds), another theme in wild animals, another in essential items and so forth.



## License

    Copyright [Nahom Agize]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.