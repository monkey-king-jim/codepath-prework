
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Wenjing Wei**

Time spent: **2** hours spent in total

Link to project: https://alabaster-rainbow-wolf.glitch.me

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
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [x] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

* Functionality Demo

![](https://i.imgur.com/GmeR7HU.gif)

* Play Demo

![](https://i.imgur.com/GQc5BRw.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
* https://alvarotrigo.com/blog/best-css-button-hover-effects/ for hover effect css on buttons
* https://www.w3schools.com/cssref/pr_text_text-align.ASP for text alignment
* https://devpractical.com/how-to-make-html-button-without-border/ for removing button boarder
* https://developer.mozilla.org/en-US/docs/Web/HTML/Element/span for the usage of span element on HTML
* https://fonts.google.com/ for font selection
* https://coolors.co/ for color matching
* And stackoverflow.com for any technical-related questions


2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    _The challenge I encountered in creating this submission was to create a better player experience on this simple game. When I followed the given instruction to create a basic working prototype of this Light & Sound Memory game, I started to ask myself that if I am a player of this game instead of the developer, would I be interested in keep playing and feel engaged to use this web game? And to be honest, my initial answer was that I felt this game was more closely resembled to a Powerpoint slides rather than a fun game. So, the first fix I implemented was to improve the aesthetic aspect of my web. I browsed a dozen of other web games, and I found out what the ones that made me click had in common was they all had visual elements matched the vibe of their games. Therefore, I changed the color scheme to a more modern design and used the font that has been used on arcade games to catch the eyes on the players. However, after this fix, I still sensed a lack of interaction with my web game from a player’s perspective, and I struggled at solving this issue because I had no knowledge on how to create the right interactions within my web. To overcome this, I started to do some research and turned to the help of online web development community. I learned many common methods that could add “depth” to the web and make it more interesting and interactive. Then, I started to try them out on my web game and kept ones that worked well with it. For instance, I applied a hover effect to transform the button a slightly larger and a pointer cursor effect to give the player a clearer idea of the interactive elements of this web. As a result of all those efforts, I think my simple web game is able to deliver a better player experience than it was before._


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

    _I wanted to know a better practice in web development to organize the functions created in Javascript. When I completed this project, I realized that even for this simple project, one would need write numerous functions and function calls to enable the functionalities of the web. I constantly found myself scroll up and down to trace the function call or to make changes. I imagine it would be really difficult to add additional functionality or to maintain/update the exisiting code by organzing the script this way. I think in practice this would be very useful to know a better way to organize the script/variables/functions._
    
4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    _If I had a few more hours to work on this project, I would spend time to adding more additional features. I think the game itself is still incomplete in a sense that the player would quickly feel bored about this game due to the lack of features. One of the main feature that is lacking is the varability in the game pattern. Currently, the game has a fixed number of buttons and levels, and I think it would be more interesting to the user if the game becomes more challenging as the level progresses. For example, instead of a fixed number of buttons and levels, I could challenge the user for how many levels he/she could reach and add a function to create an additional button for each 3 levels. Consequently, I would also need to include a level record variable in the script and also a leader board element in the HTML file. I think those additional features would create more fun for players to keep enjoying the game._


## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/lTcw_3pfNQE)


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
