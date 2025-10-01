# Project 2 - *Wordle 2*

Submitted by: **Olaoluwa James-Owolabi**


**Wordle** is a Wordle clone that implements core gameplay features (enter letters, delete letters, submit guesses) and custom settings (themes, alien mode, reset button).

Time spent: **1** hours spent in total  

## Required Features

The following **required** functionality is completed:

- [x] User can change the number of letters per row (the length of the goal word)
- [x] User can change the numbers of rows on the board (how many guesses allowed)
- [x] User can select a new themed set to pull the goal word from
- [x] User can select "alien wordle", causing the goal word to change after each guess


The following **optional** features are implemented:

- [x] App displays a reset button on the top left to reset the game (but make no changes to the settings)

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

![Worlde2Recording.gif]

## Notes

- Understanding how closures pass events from `KeyboardCell` → `KeyboardController` → `ViewController`.  
- Debugging why letters weren’t showing until `numberOfItemsInSection` was implemented correctly.  
- Differentiating between `resetBoard(with:)` and `resetBoardWithCurrentSettings()`.  


## License

    Copyright [2025] [Olaoluwa James-Owolabi]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
