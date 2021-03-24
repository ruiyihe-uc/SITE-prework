# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ruiyi He**

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/rainy-aluminum-exhaust

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
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] Show round/turn number
- [ ] Show record of rounds winning/lose
- [ ] Buttons to select difficulty of the game
- [ ] Different levels of difficulty (e.g. different playback speed, different length of pattern)

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Clicking on each button:

![](https://i.imgur.com/ckSh5rg.gif)

Start the game:

![](https://i.imgur.com/ZY2ZsVj.gif)

Stop the game half-way:

![](https://i.imgur.com/3P94ECF.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

    Color: 
            
            https://www.w3schools.com/cssref/css_colors.asp

    Web-safe fonts: 
    
            https://www.w3schools.com/css//css_font_websafe.asp
    
    Math.random: 
    
            https://www.w3schools.com/js/js_random.asp
    
    Vectors: 
             
            https://www.educba.com/vectors-in-javascript/
    
            https://www.w3schools.com/jsref/jsref_length_array.asp
            
    Insert Image as Button Background:
    
            https://pixabay.com/
    
            https://www.w3schools.com/tags/tag_img.asp
            
            https://www.w3schools.com/cssref/pr_class_display.asp
            
            https://developer.mozilla.org/en-US/docs/Web/CSS/background-size
            
    Center Arrangement:
    
            https://www.w3schools.com/howto/howto_css_image_center.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

    I am very new to web development so it was my first time coding in javascript and CSS. It was also my first time coding in three different programming languages at the same time and see how they work together to form the webpage. Although I have seen a similar application of using multiple languages to create one project using React as the base, it is the first time for me to write the code myself. The pre-work guideline helps a lot as it shows clear instructions and the w3schools and other websites provide additional resources in developing the project. When I was trying to implement the random secret pattern, I was able to google the use of math.random functions in javascript and since the basic logic behind different programming languages are similar, I was able to apply my knowledge in other programming languages to this project. For example, the use of for loop in Javascript is similar to it in Java, the only difference is that instead of using “int”, the counter is declared by “let”. I was able to overcome most challenges using resources online. Outside resources such as Google and youtube videos have helped me a lot in developing this project.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

    In this project, we only used one HTML, one JS, and one CSS file to implement the webpage. Is it possible to have more than one file of each for one webpage? If it is possible, how will it be implemented and how can we make sure the files can work together without conflicts? 

    The light and sound memory game only have one webpage. However, for many websites, users are able to navigate to another webpage by clicking on some button, how will it be implemented and will we be using URLs or file names to navigate to different sites?


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

    In addition to the recommended features, there can also be a counter showing the round/turn number of the game. It is unclear how many turns are left for the user currently and a turn counter can be helpful. A record of rounds the user is winning or losing can be another feature of the project, and it can even be implemented with a user login function. The records can be stored on the server so the users can view them anytime they log into their accounts.

    To make the game fit more users, we can also implement different levels of difficulty to the game. A higher level of difficulty can have a shorter playback speed and a longer pattern to follow. Users will be able to select demanded level of difficulty by clicking on buttons and it can also be reflected in the user’s game record.




## License

    Copyright Ruiyi He

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
