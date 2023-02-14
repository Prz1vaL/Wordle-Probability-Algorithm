# Wordle-Probability-Algorithm
## A extension of the Worlde-App using TDD Approach and following Clean Code Standard ##

### Intro : 
   1)  While working on the Wordle App, It was clear to me that I had to come up with a probability factor that could pinpoint how likely the player would be able to guess the word in 'n' attempts.
   2)  After scrolling tirelessly in the internet , Where I couldn't exactly come up with a way to integrate existing Algorithms into my code; I decided to come up with my own. 
   3) I learned the guessing behaviour of the original Wordle App by New York Times (Link : https://www.nytimes.com/games/wordle/index.html),What I was able to observe was that model was far advance and would require more time.Although  I came up with the basic version of the algorithm.

#### QUESTION / PROBLEM : 

$ Find the probability of guessing the right 5 letter word for the following conditions: 
1) Total number of words is 14855
2) Total number of attempts is 6 
3)  One word per attempt (x)
>> Find p(n) for each attempt.

Note : If 'x' word contains a character or more (but not all) of the right 5  letter word in any attempt what is the probability factor in the next attempt?


#### NOTES :

After 3 days, of asking my friends and colleagues, With everyone giving a rough idea of how to proceed; I took it upon me to reach the hidden treasure.



ROUGH WORK OF DEDUCTING THE ALGORITHM :
![ORIGINAL WORK OF WORLDE ALGORITHM](https://user-images.githubusercontent.com/113372062/218266813-9ba01c15-5a69-49bc-b1dd-67cca228538a.jpeg)

IMPLEMENTATION : <img width="1054" alt="Screenshot 2023-02-14 at 7 48 21 PM" src="https://user-images.githubusercontent.com/113372062/218848251-18432713-2a4e-4ede-aec2-accd8d93052d.png">
<img width="1054" alt="Screenshot 2023-02-14 at 7 58 57 PM" src="https://user-images.githubusercontent.com/113372062/218848265-37c43394-672e-4508-92fe-93a20e475301.png">



