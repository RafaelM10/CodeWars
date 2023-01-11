## Problem

Create a function which answers the question "Are you playing banjo?".
If your name starts with the letter "R" or lower case "r", you are playing banjo!

The function takes a name as its only argument, and returns one of the following strings:

name + " plays banjo" 
name + " does not play banjo"
Names given are always valid strings.

## Curiosity

The startsWith() method
This method is called directly on a variable of type string and returns true if the word, phrase or text starts with a specific substring and false otherwise.

**First Solution:**
```javaScript

function areYouPlayingBanjo(name) {
  if(name.startsWith('r') || name.startsWith('R')){
    return `${name} plays banjo`
  } else {
    return `${name} does not play banjo`
  }
}
```