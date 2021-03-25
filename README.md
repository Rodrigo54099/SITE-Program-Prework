# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Rodrigo Martinez

Time spent: 4 hours spent in total

Link to project: (insert your link here, should start with https://glitch.com/edit/#!/site-pre-work-project)
Note: sound may not play at first, but hitting the refresh icon next to "change url" button makes the sound play for me if this happens

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
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [x] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

Strike System:

![](https://cdn.glitch.com/0b5fcd1f-77b2-4a19-80d3-a50c4accfe19%2Fezgif.com-gif-maker6.gif?v=1616630418119)


Full Game:

![](https://cdn.glitch.com/0b5fcd1f-77b2-4a19-80d3-a50c4accfe19%2Fezgif.com-gif-maker.gif?v=1616628857912)
![](https://cdn.glitch.com/0b5fcd1f-77b2-4a19-80d3-a50c4accfe19%2Fezgif.com-gif-maker3.gif?v=1616629111213)
![](https://cdn.glitch.com/0b5fcd1f-77b2-4a19-80d3-a50c4accfe19%2Fezgif.com-gif-maker4.gif?v=1616629446689)


Start/Stop New Game:

![](https://cdn.glitch.com/0b5fcd1f-77b2-4a19-80d3-a50c4accfe19%2Fezgif.com-gif-maker5.gif?v=1616630152866)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

Websites:

1)https://developer.mozilla.org/en-US/docs/Web/CSS/background-size#contain

2)https://www.w3schools.com/js/js_random.asp

3)https://www.w3schools.com/cssref/css_colors.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)
   
One of the main challenges I encountered throughout the creation of my pre-work was making sure I had the appropriate
syntax and logic through all my files. For example, in java and C++ I am used to writing our functions with its respective
type (void, int, bool, etc) and in JavaScript, or at least for this project, I noticed that we are only defining functions
with the word "function". I have previous experience with HTML, CSS, and JavaScript but have not been able to refresh what
I know in these languages until recently. To make sure every section of my code was working accordingly, I made sure to
take my time reading the code that we were provided with and applied similar syntax when making a new function or editing
an already existing one. I also had a bit of trouble getting the images I found online to show up on the memory tiles at
first. I knew I needed to change the style.css file to display the image when the user clicked on the tile and to disappear
otherwise, but I kept on having the image appear outside the title. It was until I did more research that I found a way to
directly link the image source into my style.css file and make it appear if the title was clicked on from there.

3) What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   
Some of the questions I have on web development include: how to implement a database to my HTML file to record user scores?
What process is needed to share user scores with other players? Would it be possible to change the position of each memory title(to
add another layer of difficulty in case the player gets too familiar with the current layout)? These are the types of questions
I have regard the improvement of my pre-work. I was able gain good understanding of what each function and command does for my
pre-work at the present moment. In addition, I also had a question pertaining to the way I was able to include images to my memory
tiles when clicked on. I noticed that the suggested way to add images to the memory tiles was by using the image tag in the HTML file.
However, I found a different method my linking the image address to my background image in my CSS file and changing the dimensions
of the image from there. Is this a valid method to implement? or would the method that involved using the image tag in the HTML file
be a more clear and syntax appropriate method.

4) If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

If I had a few more hours to work on this project, I would try my best to implement a new game mode! Before the user is
brought up to the memory titles, I would add a feature that lets the user try classic mode(this mode) and an infinite
mode. The infinite mode would keep the user playing until he gets a title wrong (or uses up his three strikes) and would
end by showing him a score board with the highest score he has achieved. I would also just try to make the game more visually
appealing to the user. For example, instead of getting a pop up message from the website telling the user he or she made a
mistake, I would try to implement a visual strike tracking system that turns a circle from green to red to signify that the
user has made a mistake.

## License

    Copyright [RODRIGO MARTINEZ]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
