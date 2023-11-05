## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)


## Overview

### The challenge

Create a user friendly webpage. It needs to be polished with the recipe, and needs to be accesible.

### Screenshot
Below is the Desktop View of my web page:

![Desktop view](/images/betterCSS.png)

Below is the Mobile View of my web page:

![Mobile view](/images/mobile1.png)
![Mobile view](/images/mobile2.png)

### Links

- Live Site URL:(https://cpuening8416.github.io/Portfolio-Project/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I Learned a lot about CSS Grids and the CSS Grid Items. It makes design web pages a lot simpler in terms of divs and specific layouts that would require a lot of additional work and sometimes a lot of confusion. A piece of code that I am proud of is displayed below because it is a mobile first build and includes the use of CSS grids.


```css
@media(max-width: 800px)
{
	.grid-container{
		background-color: #9EBFB5;
		display: grid;
		grid-template-areas: 
		'top top top top top top'
		'bottom bottom bottom bottom bottom bottom';
		text-align: left;
		margin: 0 auto;
	}
	
	.grid-item2{
		grid-area: top;
		border-radius: 10px;
		padding: 5%;
		width: 70%;
		margin: auto;
	}

	img{
		max-width: 110%;
		height: auto;
		border-radius: 10px;
		margin: 0 auto;
	}

	.grid-item1{
		grid-area: bottom;
		padding: 2%;
		border-radius: 10px;
		max-width: 85%;
		height: auto;
		align-self: center;
		margin: 20px 10px 10px 10px;
	}
	
}
```


### Useful resources

- [CSS Grid Item](https://www.w3schools.com/css/css_grid_item.asp) - This helped me for figuring out understanding how to set up and use CSS grids. I really liked this feature and really look forward to using it again in the future.



