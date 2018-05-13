# Kids Web
## Lesson 5: Arrays and Random

### What is an Array?
- Use analogy of a large container with lots of different things in it, compared to lots of little drawers with only one thing in each drawer. Which is easier to find things?

In the following code, how do we get the name of the middle person?
`var team = "Jimmy,Sally,Betty";`

Enter arrays!

`var team = ["Jimmy","Sally","Betty"];`

Now, to find the middle person we just use the index.

`team[1]`

Note: Talk about starting at zero

### Randomness

* Math.random -- 0-1
* Math.floor -- rounds to nearest whole number

### Magic 8-Ball
    <doctype !html>
    <html>
      <head>
        <title>Magic Fortune</title>
      </head>
      <body>
        <script>
          var fortunes = [
            "That sounds good",
            "Yes, you should definitely do that",
            "I'm not sure that's a great idea",
            "Maybe not today?",
            "Computer says no"
          ];
        </script>
        <h1>Magic Fortune</h1>
        <button 
          onclick="document.getElementById('response').innerHTML = 
          fortunes[Math.floor(Math.random() * fortunes.length)];">Ask me</button>
        <p id="response"></p>
      </body>
    </html>