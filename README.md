# Cards Against Humanity Simulator
Simulate playing the game Cards Against Humanity & generate a relative frequency histogram of the number of rounds played
before a winner is declared. My underlying assumptions are that each round a serf (a player who is not the card Czar) is
chosen randomly from a uniform distribution and elected as the new card Czar.

The histogram is generated by replaying the game one million times. The default values are 13 players with 5 points needed
to win.

The probability density function is very similar to the `uniform sum distribution` with the exception that each round a
random player is removed from the selection process.

## Example of program output
![alt text](https://github.com/carlcorder/cards.against.humanity/blob/master/src/img/cards-against-humanity-histogram.png)

### Requirements
* Java 8
* Maven

### Running
* Run the main class in your favorite IDE

#### TODO
- [ ] Package as jar and allow user to run with command line parameters
