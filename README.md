# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

## Overview

### Screenshot

![](\assets\images\site-preview.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

By adopting a mobile-first workflow, I streamlined the development process for this project. While responsive web design initially presented challenges, this project provided a valuable opportunity to hone my skills in creating adaptable websites using media queries and a diverse range of HTML and CSS tags.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I have acquired proficiency in developing responsive websites, effectively utilizing various HTML and CSS tags to achieve optimal functionality and aesthetics.

```html
<table>
  <tbody>
    <tr>
      <td>Calories</td>
      <td><strong>277kcal</strong></td>
    </tr>
    <tr>
      <td>Carbs</td>
      <td><strong>0g</strong></td>
    </tr>
    <tr>
      <td>Protein</td>
      <td><strong>20g</strong></td>
    </tr>
    <tr>
      <td>Fat</td>
      <td><strong>22g</strong></td>
    </tr>
  </tbody>
</table>
```

Key Media Queries and HTML Tags for Responsive Web Development That Helped me

```css
@media (min-width: 767px) {
  body {
    width: 50%;
    background-color: hsl(327, 91%, 96%);
    margin: auto;
    padding: 5% 0;
  }

  .container {
    background-color: #fff;
    padding: 4% 4% 0;
    border-radius: 35px;
  }

  .container .image img {
    border-radius: 25px;
  }

  .container .recipe h1 {
    font-size: 45px;
  }
}
```

### Continued development

For future endeavors, I aim to continue leveraging a mobile-first workflow, semantic HTML, and responsive design principles. To enhance my technical skills, I plan to delve deeper into table structures and styling techniques. Additionally, I will prioritize writing clean, well-commented code to improve readability and maintainability.

### Useful resources

- [Responsive Web Design - Media Queries](https://www.w3schools.com/css/css_rwd_mediaqueries.asp) - This helped me with media queries for responsive web design. I really liked this pattern and will use it going forward.

## Author

- Frontend Mentor - [@Zaidqureshi0995](https://www.frontendmentor.io/profile/Zaidqureshi0995)
