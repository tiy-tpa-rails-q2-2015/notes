# Week 8 - Assignment 1

## Blackjack Revisited

We're going to recreate our original Blackjack app from week one, but this time using a backend API as a service to provide the game logic.

I've deployed the API at:

    http://pure-forest-blackjack.herokuapp.com

Here's the source for that Rails app:

    https://github.com/tiy-tpa-rails-q2-2015/baas

### Requirements

- [ ] Create a command line script, called `blackjack`, no '.rb'
- [ ] Run `chmod +x blackjack` to make it executable.
- [ ] Make this the first line of your program: `#!/usr/bin/env ruby`. You can now run `./blackjack` directly on the command line to run your game. Neat!
- [ ] Your entire program should be contained in this one file, in multiple classes.
- [ ] Create a class (`Blackjack` or whatever you want to call it) to keep the HTTP requests and JSON parsing separate from all of the CLI (command line interface) code.
- [ ] Create a class (e.g. `Game` or `Interface`) that uses your 'Blackjack' class to prompt the user for their name, and to hit or stay.
- [ ] Display the all of appropriate output to play, including the players name.
- [ ] Prompt the user for their name, and to hit or stay.
- [ ] The only code written in the global/main object space in your program should be an entry point at the end e.g. `Inteface.new` or `Game.run`. You may want/need to create more classes. Try to think about a separation of concerns, each class should represent just one idea (see "SRP").
- [ ] **Bonus**: Take an optional command line argument of a game ID and continue playing that game instead of creating a new one.


### Resources

[My partial demo of using Net::HTTP and our Blackjack API](https://gist.github.com/ambethia/8fb95a03fb9cb7ec5505)
[Net::HTTP Ruby Docs](http://ruby-doc.org/stdlib-2.2.2/libdoc/net/http/rdoc/Net/HTTP.html)
[Peter Cooper's Net::HTTP Cheatsheet](http://www.rubyinside.com/nethttp-cheat-sheet-2940.html)
