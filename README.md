# Hubot Trivia Game Plugin

A trivia bot.

## Commands

*   **!trivia** - ask a question
*   **!skip** - skip the current question
*   **!answer <answer>** or **!a <answer>** - provide an answer
*   **!score <player>** - check the score of the player

## Installation

* In your hubot installation's path:
* `npm install hubot-trivia-game --save`
* edit `external-scripts.json` and add `hubot-trivia-game` to the JSON array.
* if the file doesn't exist, create it with `["hubot-trivia-game"]`

### Question DB

The question database is a file containing a JSON array of questions with the following properties:
```
{
  "answer": "Pizza",
  "category": "FOOD",
  "question": "Crust, sauce, and toppings!",
  "value": "$400"
},
```
