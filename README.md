# Frontend Mentor - Profile Card Component Solution

<div align="center">

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![NEWBIE](https://img.shields.io/badge/Frontend_Mentor-NEWBIE-3DB8FF?style=for-the-badge)

</div>

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [What I Learned](#what-i-learned)
- [Built With](#built-with)
- [Author](#author)

---

## Overview

### Screenshot

![Design preview for the Profile card component coding challenge](preview.jpg)

### Links

- Solution URL: https://juansanchezzzzz.github.io/Profile-card-component/
- Live Site URL: https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ

---

# What I Learned

## Semantic HTML Structure

I learned that components should be organized into logical sections instead of creating unnecessary nested containers.

```html
<article class="card">
    ...
</article>
```

Using semantic elements helps keep the markup cleaner and easier to maintain.

---

## Using Multiple Background Images

I learned that CSS allows multiple background images separated by commas.

```css
background-image:
    url("./images/bg-pattern-bottom.svg"),
    url("./images/bg-pattern-top.svg");
```

Each image can have its own position and repeat values.

---

## Understanding `background-position`

I learned that `background-position` can receive keywords and offsets to position backgrounds more precisely.

```css
background-position:
    left 50vw top 50vh,
    right 50vw bottom 50vh;
```

This helped me understand how decorative SVG backgrounds can be placed partially outside the viewport.

---

## Matching Positions to Multiple Backgrounds

When multiple backgrounds are used, CSS matches each position to its corresponding image.

```css
background-image:
    url(a.svg),
    url(b.svg);

background-position:
    left top,
    right bottom;
```

```text
Image 1 → Position 1
Image 2 → Position 2
```

Understanding this relationship made it easier to work with layered decorative backgrounds.

---

## Limiting a Background to Part of a Component

I learned that a background image can be visually restricted to a section of a card using `background-size`.

```css
.card{
    background-image: url("/images/bg-pattern-card.svg");
    background-size: 100% 8rem;
    background-repeat: no-repeat;
}
```

This allowed the patterned header to occupy only the top area of the card while keeping the rest white.

---

# Built With

- Semantic HTML5
- CSS Custom Properties
- Flexbox
- Multiple Background Images
- Advanced Background Positioning
- Responsive Design

---

# Author

- Frontend Mentor - https://www.frontendmentor.io/profile/juansanchezzzzz
- GitHub - https://github.com/juansanchezzzzz
