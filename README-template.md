# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout for the interface depending on their device's screen size
-   See hover and focus states for all interactive elements on the page

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   CSS Grid
-   Mobile-first workflow
-   [Styled Components](https://styled-components.com/) - For styles

### What I learned

I learnt how to work with spans and also lists.
I also learnt how to work with different colours and also box shadows
I learnt how to change the features of diffrent screen sizes using media queries

Proud of some of these code snippets

```html
<ul class="categories">
    <li class="category reaction">
        <span>Reaction</span>
        <span class="score">80 / 100</span>
    </li>
    <li class="category memory">
        <span>Memory</span> <span class="score">92 / 100</span>
    </li>
    <li class="category verbal">
        <span>Verbal</span> <span class="score">61 / 100</span>
    </li>
    <li class="category visual">
        <span>Visual</span> <span class="score">72 / 100</span>
    </li>
</ul>
```

```css
.proud-of-this-css {
    @media (max-width: 375px) {
        .results-summary {
            flex-direction: column;
            width: 300px;
        }
        .results {
            border-top-left-radius: 0;
            border-top-right-radius: 0;
        }
    }
}
```

### Continued development

I look forward to learning more on how to work with differnt colours on one element and also the hover state of elements

## Author

-   Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/SeNaTu24)
-   Twitter - [@yourusername](https://www.twitter.com/aduragbemi_24)
