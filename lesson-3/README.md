# Kids Web
## Lesson 3: Intro to JavaScript

NOTE: Keep concepts focused on client-side JavaScript for now

Using the book [JavaScript for Kids](https://www.nostarch.com/javascriptforkids) book as a reference.

### What is JavaScript?
Examples: posting messages on Facebook, or most Email web sites heavily use JavaScript

### drawCats() example

    var drawCats = function(numberOfCats) {
        for (var i = 0; i < numberOfCats; i++) {
            console.log(i + ".) =^.^= "); 
        }
    }
    drawCats(10);

### Buttons

Not necessarily part of the originally planned lesson, but was getting asked how buttons worked with JavaScript. So, went over this:

Show alert() box on a button. This was fun. `<button onclick="alert('Hello World')">`
