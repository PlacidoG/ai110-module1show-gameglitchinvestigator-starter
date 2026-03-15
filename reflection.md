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
- Give one example of an AI suggestion that was incorrect or misleading (including what the AI suggested and how you verified the result).

---

## 3. Debugging and testing your fixes

- How did you decide whether a bug was really fixed?
- Describe at least one test you ran (manual or using pytest)  
  and what it showed you about your code.
- Did AI help you design or understand any tests? How?

---

## 4. What did you learn about Streamlit and state?

- In your own words, explain why the secret number kept changing in the original app.
- How would you explain Streamlit "reruns" and session state to a friend who has never used Streamlit?
- What change did you make that finally gave the game a stable secret number?

---

## 5. Looking ahead: your developer habits

- What is one habit or strategy from this project that you want to reuse in future labs or projects?
  - This could be a testing habit, a prompting strategy, or a way you used Git.
- What is one thing you would do differently next time you work with AI on a coding task?
- In one or two sentences, describe how this project changed the way you think about AI generated code.
