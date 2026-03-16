# 💭 Reflection: Game Glitch Investigator

Answer each question in 3 to 5 sentences. Be specific and honest about what actually happened while you worked. This is about your process, not trying to sound perfect.

## 1. What was broken when you started?

- When I first used the game, it said I guessed the number on the first try and ballons and fireworks shot up.

- The 'New Game' button dosen't create a new game but changes the secret number at ('Secret) in Developer Debug Info
- When switching difficulity levels, the database dosen't update the blue highlighted prompt when changing to 'Easy' or 'Hard' based on their respected ranges. 
- Allowed attempts in the left task bar menu of the live website also dosen't update the same data point in the blue highlighted prompt when changing difficulity levels. Its off by 1 when starting the server, but when 'New Game' button is pressed, the values finally match with each other.

---

## 2. How did you use AI as a teammate?

- Claude and CoPilot
- Give one example of an AI suggestion that was correct (including what the AI suggested and how you verified the result).
- The AI suggested to change functions in logic_utlis and put it in app but that created more

---

## 3. Debugging and testing your fixes

- The game worked by executing and competing the tasks to the standard. 
- It showed that my code needed some valid testing to examine all test cases and make sure all of them pass.
- Yes by changing functions

---

## 4. What did you learn about Streamlit and state?

- The secret number changed every time the new game button was pressed
-  I would say its a python libary for building frontend dashboard applications, similar to html/css/javascript but more prone to data visulation/analysis than full scale applications
- Organized the range of numbers based on there respected difficulity level

---

## 5. Looking ahead: your developer habits

- Use more of streamlit for analysis work
- Be more descriptive on what lines to debug and make sure to reset the AI, so it dosen't overcomplicate solutions
- AI generated code should be used as a 2nd option if a coder can't figure out an error like logical but always be descriptive.
