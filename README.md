# Product-preview-card

> [!NOTE]
> This is a HTML and CSS practising project, that is meant to help me improve on my front-end coding skills. It is a challange from [Frontend-Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa)

## Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Links](#links)
- [My Process](#my-process)
  - [Technologies Used](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgements](#acknowledgements)

## Overview

### The Challenge

Create a styled webpage for a product preview card that is for a perfume

Users should be able to:

- View the optional layout on their devices screen size
- See hover and focus states for interactive elements

### Links

- Solution live preview => [product preview card]()
- Solution => [html file]() [css file](https://github.com/zondiMaqina/product-preview-card/blob/main/styling_sheets/styles.css)

## My Process

### Built With

- Semantic HTML% markup
- CSS Flexible Box module
- Media queries

### What I learnt

- [x]  I learnt about a new html element `<picture>` it should always take a fallback `img` element in case other `source` element's conditions are not met

```
<picture>
  <source srcset="link/to/image" media="(width-type: dimension")>
  ...
  <img src="path/to/image">
</picture>
```

- [x] It also turns out that using 100% for an image's dimension (width & height)  will at least cause it to follow its container's responsiveness which can be done with flexible box

- [x] Using media queries enabled me to support the card's responsiveness to the next level

```
@meadia screen and (width-type: dimension){
  ...
}
```

### Continued Development
I must carry on learning to use more semantic HTML and less media queries to avoid long loading

### Useful Resources

- [W3Scools](https://www.w3schools.com/html/html_images_picture.asp) => reference to the `<picture>` element

- [W3Schools](https://www.w3schoolscsom/css/css_rwd_images) => reference to image resposiveness
## Author

- Frontend Mentor - [@zondiMaqina](https://www.frontendmentor.io/profile/zondiMaqina)

## Acknowledgements

None at the moment, If there are any improvement or advices please be sure to let this young developer know
