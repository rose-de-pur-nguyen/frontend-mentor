# Frontend Mentor - FAQ accordion solution

This is a solution to the [FAQ accordion challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/faq-accordion-wyfFdeBwBz). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- Hide/Show the answer to a question when the question is clicked
- Navigate the questions and hide/show answers using keyboard navigation alone
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./results)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Bootstrap
- Flexbox
- Javascript

### What I learned

- Bootstrap overriding: At first it confused me a lot because just a simple task that setting background to the designated pink I still couldn't achieve, many many later on that i figure out it was because Bootstrap's affects. The easiest way to solve this is to add "!important" 
- The "classList.toggle" of Javascript: not purely new to me, but I still consider it amazing


```css
body {
  background-color: hsl(275, 100%, 97%) !important;}
```

```js
faqs.forEach(faq => {
      faq.addEventListener('click', () => {
        faq.classList.toggle('active');
      })
})
```

### Continued development

- Bootstrap: I currently know well of most of Bootstrap properties and classes, but sometimes I still forget how exactly that certain class is written so I have go and look up at the reference which is kinda annoying and time-wasting
- The content structure: my html this time is really a big mess because I still keep the basic content structure logic but not the web interface logic one (sorry if my wording is clunky)
- Javascript: the application of Js in this challenge is quite easy but I know my skill is nothing now, really need to continue on enhancing


### Useful resources

- Gemini: a powerful AI tool helping you answer all of your questions clearly. Gemini was the one helped me how to deal with the bootstrap overriding 
- Canva: I don't know if this is helpful or not, but I use canva to get the specific color code. In the question hovering part I didn't find any provided colors that matched with the mock picture, so I just cropped the pic and threw it on canva, for me it works

## Author

- Frontend Mentor - [@rose-de-pur-nguyen](https://www.frontendmentor.io/profile/rose-de-pur-nguyen)


## This is my first challenge on Frontend Mentor, I hope to receive feedbacks, maybe this one has nothing with Javascript but please check out my HTML file, because I really think it needs to be improved. 