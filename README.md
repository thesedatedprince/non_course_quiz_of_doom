This is a challenge I'm setting up for the evenings, in order to practice
my rspec/ruby and the methods taught so far on the course.

As I like games, I'm going to be creating a quiz-style game featuring
multiple classes. I've split the general functionality of the program out
into the following user stories:

```
As a game developer
So the user can have a question
I want to be able to ask a user a question.

As a user
So I can continue the game
I want to be able to answer a question.

As a game developer
So the user can answer right or wrong
I want to give the user three answers to choose from, one right, one wrong.

As a game developer
To be able to check the user's performance
I want to check if the question has been answered correctly or incorrectly.

As a game developer
So the user is penalised on an incorrect answer,
I want the user to lose one health if they answer the question incorrectly.

As a game developer,
So the user can lose,
I want the game to end if the user has zero health remaining.

As a game developer
So there is a challenge
I want to be able to ask the user multiple questions.

As a game developer
So there is a challenge
I don't want an asked question to be repeated.

As a user,
I want a way to win,
Therefore, I need an opponent to play against.

As a game developer,
So there is competition,
I want to be able to ask the opponent a question.

As a game developer,
So the competition is balanced,
I want the software to ask the user and opponent a question alternately.

As a game developer,
So the competition is balanced,
The opponent should be able to answer questions.

As a game developer
To be able to check the opponent's performance
I want to check if their question has been answered correctly or incorrectly.

As a game developer
So the opponent is penalised on an incorrect answer,
I want the opponent to lose one health if they answer the question incorrectly.

As a game developer,
So the opponent can lose,
I want the game to end if the opponent has zero health remaining.

As a user,
So I know I have won,
I need a victory message if the opponent hits zero health.
```
