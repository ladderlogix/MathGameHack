# Math Game Cheat
[https://www.purposegames.com/game/unit-circle-degrees-and-radians-game](https://www.purposegames.com/game/unit-circle-degrees-and-radians-game)

## What is the Game

## Cheat
```javascript
const divs = document.querySelectorAll('div');

for (let i = 0; i < 32; i++) {

let textValue = document.getElementById('question-box').textContent;
console.log(textValue);

divs.forEach(div => {
    if (div.getAttribute('data-text') === textValue) {
        div.click();
    }
});
}
```

## How it works
We get the te text from the question box. Then we compare that to all the div elements data-text field. If they match we simulate a click on the element
