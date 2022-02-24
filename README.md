# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
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
 To design a QR code website
### Screenshot

![Mobile](./images/moble-preview.JPG
![Desktop](./images/desktop-preview.JPG



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

Create a Tree struvture to have a overview of the tag going to be used.
Make a appropiate padding and margin size using rough draft.
Create HTML and CSS file and implement.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- flexbox



### What I learned

learned to center element using 
learned to make a appropiate padding and margin.


```html
<!DOCTYPE html>
<html>
<head>
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title> Scan QR code</title>
	<link rel="stylesheet" type="text/css" href="index.css">
	<link rel="icons" type="image/x-icon" href="./images/favicon-32x32.png">
	<link rel="preconnect" href="https://fonts.googleapis.com">
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
	<link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
	<main>
		<section id="qr-block">
		<img id="qr-image" src="./images/image-qr-code.png" height="285px" width="285px" alt="QrR code for the frontend mentor website">
		<p id="qr-para1">
			Improve your front-end skills by building projects 
		</p>
		<p id="qr-para2">
			Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
		</p>
	</section>
	</main>
	<footer >
		<p id="footer-para">
			Challenge by <a href="https://www.frontendmentor.io/home">Frontend Mentor</a>. Coded by <a href="https://github.com/mathanraj0601">Mathanraj T
			</a>.
		</p>
	</footer>
</body>
</html>

```css
*
{
    font-family: 'Outfit', sans-serif;
	padding: 0;
	margin: 0;
}
body
{
	width: 100vw;
	height: 100vh;
	background-color:hsl(212, 45%, 89%) ;
	
}
main{
	width: 100%;
	height: 95%;
	display: flex;
	justify-content: center;
	align-items: center;
	flex-direction: column;
}
#qr-block
{
	height: auto;
	width: 305px;
	background-color: hsl(0, 0%, 100%) ;
	padding: 10px;
	box-sizing: border-box;
	border-radius: 15px;

	box-shadow: 0px 5px 15px hsl(212, 45%, 89%) ;
}
#qr-image
{
	border-radius: 15px;
}
#qr-para1
{
	text-align: center;
	margin: 10px;

	padding: 10px;
	font-size: 20px;
	font-weight: 700;
	color:  hsl(218, 44%, 22%);
}
#qr-para2
{
	text-align: center;
	margin: 10px;
	margin-bottom: 20px;
	font-size: 15px;
	font-weight: 400;
	color: hsl(220, 15%, 55%);
}
#footer-para
{
	font-weight: 700;
	color:  hsl(218, 44%, 22%);
	font-size: 15px;
	padding: 10px;
	text-align: center;
}
a{
	text-decoration: none;
}
a:hover
{
	text-decoration: underline;
}





### Continued development

i like to partice more about auto value for various property. which is very helpful in reponsive layout


### Useful resources

- [Stack oveflow] - center a div suing flexbox.
- [geeks for  geeks] - Center a element using margin .



## Author

- Website - [Mathnaraj T](https://github.com/mathanraj0601)
- Frontend Mentor - [@mathanraj0601](https://www.frontendmentor.io/profile/mathanraj0601)



## Acknowledgments

i like to thank stack overflow and Geeks for geeks where i get the information to center a element.


