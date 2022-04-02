# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Annie Lin**

Time spent: **3** hours spent in total

Link to project: https://glitch.com/edit/#!/cold-sandy-scowl

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://media.giphy.com/media/ykD0YCFhmM8h6niy4j/giphy.gif)
![](https://media.giphy.com/media/qPgxOWWVoLgzDIblWI/giphy.gif)
![](https://media.giphy.com/media/tyU3lVHroC6VB8Wi2j/giphy.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- https://stackoverflow.com/questions/34966459/creating-array-of-length-n-with-random-numbers-in-javascript
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I encountered when completing this assignment was correctly implementing the guess function. I initially attempted to write my own game logic, however, when I tested my code using the preview, I noticed that my game would end prematurely — the "You lost" alert would show up even though I correctly followed the pattern. I compared my logic with the solution to find that they did achieve the same result, so I replaced my code with the solution code. However, even when doing this, I still ran into the same issue. To overcome this, I decided to debug the code using print statements with console.log(). I found that my playClueSequence function was not resetting the guessCounter, even though there was a statement that reset guessCounter to 0. This interfered with the conditional logic in the guess function. After locating the problem, I checked if functions were running as expected with more print debugging, as well as if I had any misspelled variables. Everything still looked fine then, so I referred to the CodePath Slack channel for help. I found someone who had the same issue as I did and their code was correct also. They were advised to recopy and paste the JavaScript code from the prework guide. I followed suit and found that my game finally worked, so I believe I may have forgotten something minor when following the prework guide.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing this project, I am interested in learning more about what an IDE is and how it works. Specifically, I am curious about whether it is required to build a website using an IDE, or whether it is simply a tool that makes website building easier. I also wonder which parts of this particular project are considered front-end and which are back-end, especially since the design of the site/game is simple (although, since it is simple, would it be easier or more difficult to identify back-end vs. front-end?). Additionally, I'd be interested in seeing how website launches work. With Glitch, it each new modification is automatically reflected on the live site, but for company websites that have a continuous stream of audiences, how are they able to modify and test the site privately while the current version of their site is still functional for its users? 


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had additional time to work on this project, I would to finish implementing the rest of the optional features, since I unfortunately found out about the opportunity the same day as the deadline. In addition to the optional features, I would create even more visual features to the game. For example, while the dialog box with the "Game Over" message suffices, I would like to implement a banner that would relay the same message, but match the design of the game. I think I would be able to make it a hidden element and reveal it when "Game Over" conditions are met in the guess function. I would also be interested in adding a website thumbnail, although I would have to do some further research on how to do so. As for adjusting functions, I would want to develop a potential equation that would generate the speed of the next clue playback, instead of decreasing it by some number of my choice.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.