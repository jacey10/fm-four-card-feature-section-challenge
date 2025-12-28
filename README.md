# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Acknowledment] (#acknowledgements)


## Overview

### Screenshot
![](./assets/images/FireShot%20Capture%20022%20-%20Frontend%20Mentor%20-%20Four%20card%20feature%20section%20-%20[127.0.0.1].png)


### Links
- Solution URL: (https://github.com/jacey10/fm-four-card-feature-section-challenge)
- Live Site URL: (https://jacey10.github.io/fm-four-card-feature-section-challenge/)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned
- I've worked with Grid before but that was for a 2 column layout. This four card feature section challenge helped me learn and understand grid row and grid column very well. Also, I used a wrong css grid property (grid-area) to position the third/orange card below the red card in the middle column. Even though it worked, I learnt that it was wrong and the reason why it worked was because of "grid-auto-placement", where browsers automatically position grid items into the first available space. So, I used the right properties instead, i.e., gird column and grid row.

- I struggled with centering the cyan and blue card (which are in the first and third column respectively) vertically in their cell. So. I used this instead;

```css
.cyan-card, .blue-card {
  transform: translateY(50%);
}
```

and it worked well.

- Initially, I gave the cards height and width (using css clamp function) but realised that the layout didn't look good visually. So, I looked up someone's solution and noticed they never used any height or width, and yet their site was responsive. I did the same thing thing and everything was perfect. Using flexible unit for grid-template-column allows me to distribute available free space within the grid container among the columns and rows. The grids (and the cards) were automatically responsive.


### Continued development
- I would continue to explore how to create layouts that are responsive across many screens and devices.


### Useful resources
I used ChatGPT for simple suggestions. For example, I learned using ChatGPT that it isn't wrong to have a paragraph of text above h1 heading.


## Author
- Website - [James Chima](https://www.your-site.com)
- Frontend Mentor - [@jacey10](https://www.frontendmentor.io/profile/jacey10)
- Twitter - [@jacey_opara](https://x.com/jacey_opara)


## Acknowledgments
- I mentioned above that I looked up someone's solution when I got stuck trying to make my grid layout responsive and realised that he never gave any height or width to the cards and his project was perfect. I did the same and mine was perfect too. This is the link to  his repo:

[Nathan's Solution](https://github.com/Nathan-Front/four-card-feature-section-master)



