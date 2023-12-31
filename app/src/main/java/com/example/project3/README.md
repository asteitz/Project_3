# Project_03 - Arithmetic App
<span style="font-size: smaller;"><strong>Ashley Steitz and Jacob Fritz worked on this as partners</strong></span>

---
<span style="font-size: smaller;"><strong> Description </strong> </span>
In our efforts to complete Project 03 we implemented an interactive Ui (User Interface) that allows the user to select a arthmitic game that caters to their level of skill.
This includes selections of difficulty level and different arithmetic operators using radio buttons.

This app allows for 3 levels:
- Easy (numbers 1 - 10)
- Medium(numbers 1 - 25)
- Hard (numbers 1 - 50)

And 4 Arithmetic Operators:
- Multiplication
- Division
- Addition
- Subtraction

As well as the user to select how many questions they will be asked using "+" and "-" to add or subtract the number of questions before pressing the "Start" Button to begin the game.

To begin we have added 3 fragments that show the differing stages of the player's placement in the app. Fragment 1 is the selection screen that contains Radio Buttons that help makes the 
selection easy and simple by the user. Then we have a '+' and '-' button to help them select how many questions they will be asked. Finally the large "Start" button is pressed to take them 
to the next screen to begin the arithmetic game!

Fragment 2 handles the difficulty level as well as the operator selection to produce the right content for the user. Once they complete the total number of questions they press the "Done" button.
This takes them to the final fragment page.

Finally, Fragment 3 displays the score of the player and offers a "Retry" button to take them back to the start to play the game again!

## Functionality
'*' indicates tested in GIF  
The following **required** functionality is completed:
<br>
_the number sequence is randomly generated and is not easily replicated_
<br>
Safeargs was implemented to transfer data from fragment to fragment. That was we can access our equations and solutions in fragment 2 and the final score in fragment 3

**Demonstrated** 4753
* [Easy] [Subtraction] [2 Questions] [ 8 - 8 = 0 | 10 - 6 = 4 ] [Done x 2 (after each problem)] [SCORE (2/2)] [Retry]  
* [Medium] [Division] [5 Questions] [1/12 = 1 | 23/5 = 5 | 6/18 = .33 | 0/21 = 0 | 18/15 = 1] [Done x 5 (after each problem)] [SCORE (2/5)] [Retry]
* [Medium] [Multiplication] [3 Questions] [ 10 x 17 = 170| 25 * 22 = 232|9 * 4 = 36] [Done x 3 (after each problem)] [SCORE (2/3)] [Retry]
* [Hard] [Addition] [10 Questions] [30 + 26  =  56 |43 + 9 = 52| 49 + 10 = 59| 37 + 41 = 53| 2 + 22 =24 | 34 + 42 = 75| 14 + 8 = 31 |40 + 23 = 63| 12 + 18 = 40|41 + 18 = 12|Completed] [Done x 10 (after each problem)] [SCORE (5/10)] [Retry]
* [Medium] [Subtraction] [3 Questions] [18 - 25 =  122| 18 - 6 = 12 |20 - 5 = 15] [Done x 3 (after each problem)] [SCORE (2/3)] [END]


---
## Video Walkthrough
Watch a demonstration of each difficulty level and operation demonstrated in the gif available on Github
Here's a walkthrough of a few cases:

<img src='https://github.com/jfritz25/Project3/blob/master/app/src/main/java/com/example/project3/RecordingProject3.gif' title='Project3 Video Walkthrough' width='50%' height = '50%' alt='Video Walkthrough' />

GIF created with [CloudConvert](https://cloudconvert.com/).

## Notes
UI Challenges:
- Obtaining the rounded edges using on the buttons
- Connecting the fragments
- Changing the version our gradle was using
- Adding in the necessary dependencies
- Using the linear and relative layouts to have the items site next to each other
  - specifically the radio buttons
- Understanding the Nav graph component

Backend Challenges:
- Implementing a way to pass items through safe args rather than bundles
- Understanding the inflating of views
- How to utilize onCreate() versus hard coding outside then calling it on inflate
- Passing items from one fragment to another

## License

    Copyright [2023] [Ashley Steitz, Jacob Fritz]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
