# Pavel Sakovich CV 
![Pavel Sakovich](images/pasha.jpg)

**Full name:** *Pavel Sakovich*  
**Phone number:** *+375(29)854-76-03*   
**E-mail:** *sake211091@gmail.com*   
**github:** [Pavel-Sake](https://github.com/Pavel-Sake)    
**English:** *A2*   
**Skills:** *HTML, CSS, JavaScript, git, БЭМ, React, Redux*
---    


I graduated from [Minsk State Energy College](http://newmgek.unibel.by/) in 2011.
I am an electrician, my experience is 9 years and achieved high results.
I study English in online courses [puzzle-english](https://en.puzzle-english.com/).  I also study HTML, CSS, JavaScript and I am good at.
And I graduated from online courses [html academy](https://htmlacademy.ru/profile/id1017129/achievements) and [codecademy](https://www.codecademy.com/profiles/course4639845410).
Examples of my project can be found on these links:

* **Riddles:** [code](https://github.com/Pavel-Sake/riddles), [site](https://pavel-sake.github.io/riddles/);
* ***Stopwatch:*** [code](https://github.com/Pavel-Sake/stopwatch), [site](https://pavel-sake.github.io/stopwatch/);
* ***Memory-Game:*** [code](https://github.com/Pavel-Sake/Memory-Game), [site](https://pavel-sake.github.io/Memory-Game/);

---

From the courses I want to gain experience in the development of websites,
applications, improve my knowledge in JS, CSS, HTML, and also learn React and Redux.
After completing the courses, I want to apply for a job as a frontend developer.

---

##### HTML

```
<div class="startPage">
    <h1 class="startPage__header">Memory Game</h1>
    <button type="button" class="playButton">Play</button>
    <button type="button" class="settingsButton">Settings</button>
</div>
```

##### CSS

```
.startPage {
    width: 100%;
    height: 100%;
    background: #000208 url("../images/background/brick-wall.png") repeat;

    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
}

.startPage__header {
    font-size: 100px;
    text-shadow: #ded8d8 5px 5px 10px;
}
```

##### JS
```
playGameButton.addEventListener('click', handleClickPlayGame);

function handleClickPlayGame(event) {
    startPage.classList.add('hiddenPage');
    gamePage.classList.remove('hiddenPage');

    let themeName = getThemeCard();
    themeCardsName = themeCard[themeName];

    getGridParameters();
    numberOfCards = columns * rows;

    setGrid(columns, rows);
    const cards = getCards();
    setCardsToCardsElement(cards);
}
```


