# Blue Ivory Group Software Engineer Challenge - Backend
## Introduction
Create a simple Blackjack API using Node.js and MongoDB

​
## Requirements
###  Game functionalities we like to see 
Must be a RESTful HTTP API listening to port 8080 (or you can use another port instead and describe in the README)
The API must implement endpoints with path, method, request and response body as specified

- Create the MongoDB database Schema
- Create an endpoint to initiate the game, with a deck of 3 packs of cards (52x3), returning shuffled deck, players initial cards
- Create an endpoint to draw cards to specific player from current deck
- Create an endpoint to draw cards to Dealer using a hand evaluation algorithm from current deck
- Create an endpoint to save the state after each rounds
- Create an endpoint to get the history for a given player

Please note that we are not necessarily expecting you to build all requirements. Build as much as you can. We are not expecting you to build the full game with no mistakes on the rules. We allow rules to be broken if you are not able to build it in a decent amount of time. (Ace management can be tricky).

### Bonus:
- ES6+
- Type checking (Typescript…)
- Chaining
- Test Pyramid
- mongo-unit

​### Other
1. Instructions on starting your application
2. Use git
3. Test cases (at least unit tests for major functions)
4. Instructions on creating a production build
​

## Submission
### **!!!!Important!!!!**
If you submit as a public git repository:
- `Avoid words like “Blue Ivory Group” and “challenge” in your repository.`
- `Do not copy any part of this file`  

Alternatively, you may also send us a ZIP archive file containing your solution. For fairness’ sake, you must also use Git and include the `.git` directory in the archive if you submit a ZIP archive file.

If you are so inclined, you can deploy the application onto a remote server (e.g. heroku) in addition to sending us your Git repository.
​
## FAQ
### What frameworks/libraries can I use?
> ** Node.js**, We judge your submission on engineering practices (over-engineering will be penalized).
### How much time should I spend on completing this challenge?
> You can work on your own schedule, but a complete solution is expected within seven days.
### Do I need to deploy somewhere?
> See `Submission`.
