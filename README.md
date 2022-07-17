# Welcome! 👋

## Fullture Course Challenge - website Css3 - Html5 🚀🚀

This is a solution for the Fullture Course Challenge, which was developed into a Super Heroes store website, to test my knowledge in `HTML5` and `CSS3` acquired in
_**Full-Stack JavaScript**_ course module from [Fullture](https://www.fullture.com/dev-full-stack/ "link to fullture website").

## Table of contents
- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
##

## Overview

### The challenge:
---

- Creation of the formatting for the contents using _**selectors**_.
- Structuring _**HTML**_ with _**semantic tags:**_
```html
<header>, <section>, <article>, <nav>, <aside>, <main>, <footer> and <figure>
```
- Code _**CSS**_ for formatting the _**semantic tags**_.
- Format _**color, font size of titles, menus, texts**_.
- Format _**images, correct dimensions, thumbnail, border-radius**_.
- Format the _**menu created with lists.**_
- _**CSS**_ properties for sizing and positioning an element.
``` css
margin, border, padding, width and height
```
- Use of the property _**position.**_
- Use of the _**Flexible Box Module**_ to spatially organize the elements, aligning and distributing spaces
between items in a container
- Use of _**CSS Grid**_ in the creation of layouts.
- Responsive Design using _**Media Query.**_

### Links

- [solution URL](https://github.com/MarcoFranca/DesafioFulltureSite.git)
- [live site URL](https://marcofranca.github.io/DesafioFulltureSite/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Grid Layout
- desktop-first workflow

### What I learned

I reinforced the concepts of html `semantic tags` and `form`

```html
       <div>
            <form class="register" action="">
                <div class="contact-form-input">
                    <input type="text" placeholder="NOME"><br/>
                    <input type="email" placeholder="EMAIL"><br/>
                    <input type="tel" placeholder="TELEFONE"><br/>
                </div>
                <div class="contact-form-text">
                    <textarea name="" id="" cols="30" rows="10" placeholder="Como podemos ajuda-lo?"></textarea>
                </div>
                <button class="btn btn-slin btn-contact">ENVIAR</button>
            </form>
        </div>
  ```
---
I reinforced my CSS knowledge in `flex-box` , `grid layout`, `border radios`, `@media query` and `placeholder`.

---
```css
.about-us{
    display: grid;
    grid-template-columns: 50vw auto;
    grid-template-rows: 200px auto;
    height: 100vh;
    background-image: url("../../images/thor_header.jpg");
    background-size: cover;
    background-position: top center;
}

.about-us-text{
    grid-column-start: 2;
    grid-column-end: 3;
    padding: 0 5vw;
}

@media screen and (max-width: 768px){
    .about-us {
        display: flex;
        height: 70vh;
        flex-direction: column;
        text-align: center;
        justify-content: center;
        background-image: linear-gradient(#fe7467, #fc3836);
        background-position: center;
    }
    
    .contact-form-text textarea::placeholder{
    padding-top: 15px;
    text-align: center;
    font-size: large;
    color: #dcdddd;
}
```

### Continued development

I will dedicate myself to future projects using javascript concepts along with html and css which I am studying and improving myself


## Author

- Linkdin - [Marco Tullio Franca](https://www.linkedin.com/in/marco-franca/)
- Frontend Mentor - [@MarcoFranca](https://www.frontendmentor.io/profile/MarcoFranca)

