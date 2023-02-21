# Quiz: Creating a Neapolitan Deck Class

## Background
A **Neapolitan Deck** of cards contains 40 cards total - the numbers 1 through 10 in four different suits (*swords, coins, cups and batons*). This is in contrast to the more familiar 52 card **French Deck**, consisting of the ranks 1 (Ace) through 13 (King) in four suits (*hearts, diamonds, clubs, spades*)

You'll be writing a simple `Card` class that dovetails with an existing `Deck` class to implement a game of Solitaire.

## Instructions

0. At the top of `card.py`, write a comment with your name. **If you don't do this you will not receive credit.**

1. Write the `__init__` method to create a `Card` object that has two attributes: an integer value from 1 to 10 and a suit given as a string.

2. Write a `__repr__` method that returns a string that is similar to the code used to create the object. (The pattern we've been using in class)

3. Write a `__str__` method that returns a string that reads as the name of the card would be spoken. For example, `str(Card(3, "Cups"))` should return "3 of Cups"

4. Write an `__eq__` method that returns true if two different cards have the same value. This will be similar to the way you implemented `__add__` in your homework for `Vector2d`

5. Commit your work and push it to your fork.