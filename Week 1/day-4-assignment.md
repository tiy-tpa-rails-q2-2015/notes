## Week 1 - Assignment #4

### Description

Create a Blackjack console game.

## Objectives

### Learning Objectives

After completing this assignment, you should be able to:

* Use control-flow (having the computer make decisions).
* Create a user interface.
* Use data-flow (your deck is a unique set of resources).

### Performance Objectives

After completing this assignment, you be able to effectively use:

* Classes
* Arrays
* Console / Terminal

### Deliverables

* A repo containing at least:

  - [ ] `blackjack.rb` -- your game. This is file you'll run with `ruby blackjack.rb`.
  - [ ] `card.rb` -- your `Card` class
  - [ ] `deck.rb` -- your `Deck` class

To submit your assignment:

* Submit a link to your repository here as a comment on this Issue and close it out.

### Requirements

- [ ] Don't consider Aces as possible 1s they are always 11s.
- [ ] This is a two hand game (dealer and player).
- [ ] No splitting or any funny business like that.
- [ ] One deck in the game.
- [ ] 52 card deck.
- [ ] No "wild" cards.
- [ ] Create a new deck every game.
- [ ] Deck must be shuffled every game.
- [ ] No betting.
- [ ] Must have suits (Ace of Diamonds).
- [ ] Dealer hits if less than 16, otherwise dealer stays.
- [ ] Player inputs if they want to stay or hit.
- [ ] Get as close to 21 without going over.
- [ ] Player beat the dealer to win.
- [ ] You can see 1 of dealers cards, while you are playing.

## Bonus

- [ ] If you get blackjack (21 with two cards), you win automagically.
- [ ] If the dealer gets blackjack, you lose.
- [ ] Add the idea of tracking your progress as you play over time.
- [ ] Let the player choose if an Ace is a 1 or an 11

## Notes

This can be fairly challenging, and may involve researching things we haven't touched on in class.

A helpful snippet of code, to give you an idea of how you might build a deck:

```ruby
# ... snip
suits = [:hearts, :diamonds, :spades, :clubs]
suits.each do |suit|
  (2..10).each do |value|
    @cards << Card.new(suit, value)
  end
  @cards << Card.new(suit, "J")
  @cards << Card.new(suit, "Q")
  @cards << Card.new(suit, "K")
  @cards << Card.new(suit, "A")
end
# ... snip
```

You don't have to use this snippet directly (and maybe you shouldn't). Also remember you can work together and help each other. Just try not to copy-pasta a solution from The Internet and do not turn in anything that you don't understand.

## Additional Resources

* [Play Blackjack](http://freeblackjackdoc.com/blackjack-game.htm)  
* [Info on Blackjack](https://en.wikipedia.org/wiki/Blackjack)
