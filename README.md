Pet Adoption
This was a 2 part series of websites. They are very similar in content, but very different in
how they are created. The 1st one was entirely html and css, and no javascript. The second
one is a single page app in Javascript using event listeners to sort the animals.

## Motivation
The motivation behind this to give us a sense of how sites that seem the same can be built
very differently, and for different purposes. The sense that they could be sorting the 
same thing breaks down as the single page app could now sort with any kind of criteria with
minimal change to the way the app works. Our motivation for doing this project was to
learn more of how a single page app functions using event listneners and redrawing the dom
each time.

## Build status
MVP. These apps are not complex, but for what they were, they achieved their purposes.

## Code Style
HTML5, CSS3, Flexbox, Javascript ES6

## Screenshots

![](https://github.com/willkotheimer/pet-adoption/blob/master/petadoption1.PNG)

![](https://github.com/willkotheimer/pet-adoption/blob/master/petadoption2.PNG)

## URL

[pet-adoption1.netlify.app](pet-adoption1.netlify.app)

[![Netlify Status](https://api.netlify.com/api/v1/badges/b817e280-6642-4b31-80d0-baf82e7b95be/deploy-status)](https://app.netlify.com/sites/pet-adoption1/deploys)

[pet-adoption2.netlify.app](pet-adoption1.netlify.app)

[![Netlify Status](https://api.netlify.com/api/v1/badges/e2a6220d-32ec-449b-8bed-a2faa2113d9e/deploy-status)](https://app.netlify.com/sites/pet-adoption2/deploys)

## Features
This site features the ability to sort by animal in a single page application

## Code Example
```
const makeAll = () => {
    const animal = 'all';
    makePets(animal);
}

const drawPets = (allmypets) => {
    var element = document.getElementById('pets');
    element.innerHTML = allmypets;
}

const addEvents = () => {

    const dogbutton = document.getElementById('dogbutton').addEventListener('click', makeDogs);
    const catbutton = document.getElementById('catbutton').addEventListener('click', makeCats);
    const dinobutton = document.getElementById('dinobutton').addEventListener('click', makeDinos);
    const allbutton = document.getElementById('allbutton').addEventListener('click', makeAll);
}
    

```
## Github owner

[Will Kotheimer](https://github.com/willkotheimer)
