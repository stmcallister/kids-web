# Kids Web
## Lesson 3: Intro to JavaScript

*NOTE: Keep concepts focused on client-side JavaScript*

Using the book [JavaScript for Kids](https://www.nostarch.com/javascriptforkids) book as a lesson plan reference.

### What is JavaScript?
Examples: posting messages on Facebook, or most Email web sites heavily use JavaScript

Sites with Cool Uses of JavaScript

* [http://lights.helloenjoy.com/](http://lights.helloenjoy.com/)
* [http://patatap.com/](http://patatap.com/)
* [http://www.histography.io/](http://www.histography.io/)
* [https://www.cubeslam.com](https://www.cubeslam.com)

### What can you do with code?
The school chromebooks have the browser console disabled. So, we'll be using [https://jsconsole.com/](https://jsconsole.com/) 

### Let's try some math

* 3 + 4
* 5 + 30
* 98210 - 43214
* 14 * 8
* 222/3
* 5 + 6 * 8 / 2 - 10



### drawCats() example
    // Draw as many cats as you want!
    var drawCats = function(numberOfCats) {
        for (var i = 0; i < numberOfCats; i++) {
            console.log(i + ".) =^.^= "); 
        }
    }
    drawCats(10);
