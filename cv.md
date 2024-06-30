# Denys Moshchonskyi
## My contact:
* __email__ : geras5722057@gmail.com
* __discord__ : Denis Whisper(@Stranez)
## About me:


My goal is to understand web technologies and learn how to do magic with them.
## Skills and Proficiency:
* Basic HTML5
* Basic CSS3
* Basic JavaScript
* Basic Figma
* Basic Git and Github
## Code example:


Your coworker was supposed to write a simple helper function to capitalize a string (that contains a single word) before they went on vacation.


Unfortunately, they have now left and the code they gave you doesn't work. Fix the helper function they wrote so that it works as intended (i.e. make the first character in the string "word" upper case).


Don't worry about numbers, special characters, or non-string types being passed to the function. The string lengths will be from 1 character up to 10 characters, but will never be empty.
```
function capitalizeWord(word) {
  let res = '';
  for (let i = 0; i < word.length; i++){
    if(i === 0) {
      res += word[i].toUpperCase();
    }
    else {
      res += word[i];
    }
  }
  return res;
}
```