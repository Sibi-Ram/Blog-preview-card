 # Blog Preview card

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

#### Desktop view:
![Desktop view](./screenshots/desktop-view.jpg)

#### Modile view:
![Mobile view](./screenshots/mobile-view.jpg)

### Links

- Source Code: [view on GitHub](https://github.com/Sibi-Ram/Blog-preview-card)
- Live Site URL: [QR code Component website](https://sibi-ram.github.io/Blog-preview-card/)

## My process

### Built with


- ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
- Flexbox

### What I learned

  
 ```css
 align-self: flex-start;
 ```
  on a flex item (such as ```<p>```) to align it to the start of the cross axis, regardless of the container's align-items value. This property only affects the alignment along the cross axis (vertical if flex-direction is row, horizontal if flex-direction is column).

```css
.flex-container {
  display: flex;
  
}

.flex-container p {
  align-self: flex-start;
  width: fit-content;
 /*Make the p tag only as wide as its content, not stretching to fill the container.*/

 /*OR*/
 
  width: auto; /* ensures it only takes up as much space as needed */
  
}


```



**Key Learning:**

___To keep the```<p> ```  as a flex item and have it only take up the space of its text, use ```align-self``` for alignment, and set width: auto (which is default), and remove any flex-grow or flex-basis settings that might cause it to stretch.___


## Author

- Twitter - [SRtheDev](https://www.twitter.com/SRtheDev)
- Frontend Mentor - [Sibi-Ram](https://www.frontendmentor.io/profile/Sibi-Ram)



## Acknowledgments

This is my solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS).

