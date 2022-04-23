# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Jeevitha Niranjan**

Time spent: **4** hours spent in total

Link to project: (https://mica-intermediate-surgeon.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] None

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
* Win the game!![](https://i.imgur.com/3mkmzrS.gif)
* Lose the game ![](https://i.imgur.com/4T8EgTF.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- ww3schools
- developer.mozilla.org

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   A challenge specific to coding would be that while coding the guess function, I simply could not debug, as the game wasn’t even starting. Clicking the start button didn’t change anything, and features that were previously working also stopped working, such as the “Stop” button showing up or the printing the user’s guesses to the console log.
   To debug this issue, I commented out all of the code I wrote, and slowly uncommented each line to figure out which line was giving me the error. It turned out that I had an error with my curly brackets, which made my guess function always resort to calling the loseGame function.
   Additionally, I haven’t worked with any HTML, CSS, or Javascript in years, and getting over my imposter regarding my inexperience was one of my biggest challenges in completing this application. I grappled with my feelings, pondering whether it was even worth applying if I didn’t know HTML, CSS, or Javascript. I had a moment of awareness, where I realized that I was simply giving up before even trying to apply. After reading the tasks thoroughly, I realized that the application didn’t even require experience. I made up a requirement that didn’t even exist, and then let my imposter syndrome take over. This experience has taught me that I shouldn’t let my imposter syndrome and feelings of inexperience take over, and that there’s always time to learn what I need to do.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   Specifically for the website, I spent a good amount of time trying to figure out how to place elements as I liked using CSS, and it was a bit challenging trying to get it to scale with the size of the website. I’d like to learn how to use frameworks such as bootstrap for css to style components of the website next time.
   Additionally, I think it was challenging to have to test the entire game each time I had to debug, so I’d like to learn how to test out smaller components of the program to make debugging easier. I’d like to learn how to use React and similar libraries to structure the files better. Right now, having all the functions in one file meant that any small mistakes made (like messing up curly braces or accidentally changing variables used in multiple functions) affected the entire file
   I’m interested in learning further about how websites store information, or more specifically how they connect to and use servers. Additionally, I want to learn how to use APIs within websites to use external components that are already built.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   I would implement difficulty levels, where the user has the option to pick how long they want their pattern to be. I would also implement an endless mode, where the game continues as long as the user guesses correctly, where the game also keeps track of the user’s score and highest score. To do so, I’d take input from the user in the form of a text entry where they can type the length of the sequence, and then use that number to then randomly generate a pattern. I’d also give the user the choice to pick ‘endless mode’ with a button, where the length of the sequence is infinite. Additionally, for both of these modes, I’d add a variable to keep track of the user's highest score (in any game so far), and update this score if the progress variable in the game surpasses the highest score.
   I’d also like to try implementing the optional feature where the clue sequence gets faster as the pattern gets longer, and a feature where if the user doesn’t guess the sequence within a certain time, they lose. To make the clue sequence faster, I’d create a variable that controlled the time between tones, instead of using a constant, and decrement the variable each time the user progressed. To create a condition where the user loses if they don't guess within a certain time, I’d use functions such as setTimeout() in javascript to create a timer, and display the game losing message after the timer runs out.

## Interview Recording URL Link

[My 5-minute Interview Recording](https://youtu.be/QadlI6H--Pg)

## License

    Copyright Jeevitha Niranjan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
