---
layout: 'project'
---
# Project: Serialization and Working with Files
Estimated Time: 4-6 hours

*Don't forget to use Git to save your projects!*

## Warmup: Event Manager

In your Ruby days to come, you'll inevitably run into times when you'll be working with CSV files and imperfect data.  Seriously... there is no such thing as a perfect dataset.  Any time you find what looks like the perfect batch of data on something interesting, whether you're trying to plot airline flight delays on a map, tease out the nuggets from a master list of nonprofits, or scrape 10,000 emails to mercilessly SPAM with your latest get-rich-quick scheme, it will be full of mistakes, omissions, and misspellings.  Working with and cleaning up data go hand in hand.

### Your Task

1. [This tutorial from Jumpstart Lab](http://tutorials.jumpstartlab.com/projects/eventmanager.html) walks you through just that sort of operation. Give it a shot.

### Student Solutions

*Send us your solution so we can show others! Submit a link to the Github repo with your files in it here using any of the methods listed on the [contributing page]({{site.url}}/dir/contributing.html).  Please include your partner's github handle somewhere in the description if they would like attribution.*

* *Your Solution Here!*
* 



## Project: Hangman

Files are a great way to save and reload a game, so we'll give it a shot here.

### Your Task

You will be building a simple command line Hangman game where one player plays against the computer, but a bit more advanced.  If you're unfamiliar with how Hangman works, see [Wikipedia](http://en.wikipedia.org/wiki/Hangman_(game\)).

1. Download the `5desk.txt` dictionary file from [http://scrapmaker.com/dir/twelve-dicts](http://scrapmaker.com/dir/twelve-dicts).
2. When a new game is started, your script should load in the dictionary and randomly select a word between 5 and 12 characters long for the secret word.
3. You don't need to draw an actual stick figure (though you can if you want to!), but do display some sort of count so the player knows how many more incorrect guesses she has before the game ends.  You should also display which correct letters have already been chosen (and their position in the word, e.g. `_ r o g r a _ _ i n g`) and which incorrect letters have already been chosen.
2. Every turn, allow the player to make a guess of a letter.  It should be case insensitive.  Update the display to reflect whether the letter was correct or incorrect.  If out of guesses, the player should lose.
3. Now implement the functionality where, at the start of any turn, instead of making a guess the player should also have the option to save the game.  Remember what you learned about serializing objects... you can serialize your game class too!
4. When the program first loads, add in an option that allows you to open one of your saved games, which should jump you exactly back to where you were when you saved.  Play on!


### Student Solutions

*Send us your solution so we can show others! Submit a link to the Github repo with your files in it here using any of the methods listed on the [contributing page]({{site.url}}/dir/contributing.html).  Please include your partner's github handle somewhere in the description if they would like attribution.*

* *Your Solution Here!*
* 


*How long did these projects take you?  [Let us know!](mailto:curriculum@theodinproject.com)*




