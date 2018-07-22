# Memory-Game
This is a game for testing your memory and sharpening your intellectual skills. 

About code:

All the function names are self-explanatory and additional comments explain the more about them. I will explain each and everything as the following chunk of comment.

/*
 * set up the event listener for a card. If a card is clicked:
 *  - display the card's symbol (put this functionality in another function that you call from this one)
 *  - add the card to a *list* of "open" cards (put this functionality in another function that you call from this one)
 *  - if the list already has another card, check to see if the two cards match
 *    + if the cards do match, lock the cards in the open position (put this functionality in another function that you call from this one)
 *    + if the cards do not match, remove the cards from the list and hide the card's symbol (put this functionality in another function that you call from this one)
 *    + increment the move counter and display it on the page (put this functionality in another function that you call from this one)
 *    + if all cards have matched, display a message with the final score (put this functionality in another function that you call from this one)
 */

So the card's symbol is displayed by the function toggleCard().
The displayed card is added to an array by the function addToggledCard().
The two displayed cards are matched by the function checkForMatch().
If all cards have been matched an gameOver() function is called which calls another function stopClock() to stop the clock, also calls writeModalStats() to display a message with the final score.

Resources:

For completing this challenge project I used the following resources.

1. The webinar youtube video from Udacity content expert Mike Wales.

https://www.youtube.com/watch?time_continue=3680&v=_rUH-sEs68Y

2. The following blogpost series from FEND student leader Matthew Cranford.

https://matthewcranford.com/memory-game-walkthrough-part-1-setup/

I thank both of you for your help!
