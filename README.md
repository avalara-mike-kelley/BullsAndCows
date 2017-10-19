# Bulls And Cows
Kata exercise
 
You are playing the following game with your friend:

You write down a number and ask your friend to guess what the number is.

Each time your friend makes a guess, you provide a hint that indicates how many digits in the guess match your secret number exactly
in both digit and position (called "bulls") and how many digits match the secret number exactly but located in the wrong position
(called "cows").

Your friend will use successive guesses and hints to eventually derive the secret number. 

For example:  
Secret number:  1807  
Friend's guess: 7810  
Hint: 1 bull and 3 cows. (The bull is 8 and the cows are 0, 1 and 7.)

Write a function to return a hint based upon the secret number and your friend's guess.  
Use B to indicate the bulls and C to indicate the cows.  
In the above example your function should return "1B3C".
