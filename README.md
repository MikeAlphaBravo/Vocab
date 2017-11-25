# _Vocabulary Guessing Game_

#### _A politically more correct version of the classic Hangman, word guessing game, 6/28/2017_

#### By _**Nathan E. M. Mayer & Michael Brooks**_

## Description

_A classic children's vocabulary game built into a web app using HTML, CSS and JQuery in classic 80's retro styling. Populates words randomly to guess. For grades 2-4._

The player guessing the word may, at any time, attempt to guess the whole word. If the word is correct, the game is over and the guesser wins. Otherwise, the other player may choose to penalize the guesser by adding an element to the diagram. On the other hand, if the other player makes enough incorrect guesses to allow his opponent to complete the diagram, the game is also over, this time with the guesser losing. However, the guesser can also win by guessing all the letters or numbers that appears in the word, thereby completing the word, before the diagram is completed. (wikipedia : https://en.wikipedia.org/wiki/Hangman_(game) as accessed 6/26/2017 at 11:26am_

## Specifications

_* assume a targetWord of "donkey"_

| Rank  | Behavior          | I   |          O       |
|-------|-------------------|-----|------------------|
|1|Accept user input        |"o"  |var guess = "o"   |
|2|Accept only 1 character  |"on" | "false"          |
|3|Accept only letters      | "4" | "false"          |
|4|Guess to lower case      | "A" | "a"              |
|-|----End Code Section     |     |                  |
|5|Check is guess in targetWord| "d" | "true"|
|6| if in word push to wordBlanks| "d" | [d,?,?,?,?,?]|
|7|If guess not in WORD add to WRONG GUESS |"z"| ["z"]|
|8|Display WORD BLANKS (HTML) |*[d,?,?,?,?,?]| d  ?  ?  ?  ? ?|
|9|Display WRONG GUESS (HTML) |["z"]  | Wrong guess: z|
|10|Game over occurs at 6 incorrect guesses | wrongGuess.length === 6 | GAME OVER|
|11| Game Won occurs at revealed word | | |
|12| Increase available vocabulary |

## Setup/Installation Requirements

* _Link to program here: https://mikealphabravo.github.io/Vocab/

## User experience screenshots:

![alt text](/img/title.png)

![alt text](/img/base.png)

![alt text](/img/guess.png)

![alt text](/img/lose.png)

![alt text](/img/win.png)

## Known Bugs

_Please submit a request if you have any input bugs or issues with output._

## Support and contact details

_If you have any updates or suggestions please contact [Michael A. Brooks] or make a contribution yourself._

[Michael A. Brooks]: mailto:mikealphabravo1982@gmail.com

## Technologies Used

Built using 
* JavaScript
* HTML5
* CSS

### License

*This software licensed under the MIT license.*

Copyright (c) 2017 **_Nathan E. M. Mayer & Michael Brooks_**
