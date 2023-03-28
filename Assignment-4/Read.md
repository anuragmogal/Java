This is the directory for Assignment 4: Card It contains three files:

Main.java
Card.java
Deck.java
Operations.java contains Operations class with following three methods:

createDeck(): This is the method used to Method to create whole deck combining all the suit with vall the alues.
printDeck(): This is the method used to to print whole deck.
printCard(): This is the method used to to print first card of the deck.
sameCard(): This is the method used to randomly select a card and find its suit.
compareCard(): This is the method used to compare values of two randomly selected cards and returns the result as a string telling if they have same or different.
findCard(): This is the method used to to find card using suit and value.
dealCards(): This is the method used to print 5 random cards from the deck.
shuffle(): This is the method to shuffle the card deck and printing them.
Card.java contains InputUser class with following methods:

It contains getter and setter methods for all the private variables suit and value stored in a single Card object.
It also contains parameterized constructor with all the variables suit and value.
Main.java contains Main class with following methods:

It contains switch case where user is allowed to enter a character for particular operations.
It contains main method inside which there's switch case for menu to select operations corresponding to methods in Deck java class.
Main method catches the returned values from different methods of Operations class and display them.
