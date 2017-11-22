# Kids Web
## Lesson 3: Intro to JavaScript

NOTE: Keep concepts focused on client-side JavaScript for now

* What is JavaScript?
    * Examples: posting messages on Facebook, or most Email web sites heavily use JavaScript
* drawCats() example

    var drawCats = function(numberOfCats) {
        for (var i = 0; i < numberOfCats; i++) {
            console.log(i + ".) =^.^= "); 
        }
    }
    drawCats(10);
    
* Show alert() box on a button. This was fun. `<button onclick="alert('Hello World')">`
