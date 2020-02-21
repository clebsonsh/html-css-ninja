# html-css-ninja
Files from my learning with [Net Ninja HTML &amp; CCS Crash Course](https://www.youtube.com/playlist?list=PL4cUxeGkcC9ivBf_eKCPIAYXWzLlPAm6G)

***

## What is HTML?
### **H**yper**t**ext **M**arkup **L**anguage

- Used to structure content on a web page (images, text, form etc)
- We structure content using __HTML tags__

``` html
  <p> content </p>
  <a> link </a>
  <img src="some-file.jpg" alt="alternative description">
```

- Some tags have a closing tag, ex: `<p> content </p>`
- Some tags don't have a closing tag, ex: `<img src="some-file.jpg" alt="alternative description">`
- When we view a web page, is just a HTML file. Those tags tell the browser 
what type of content we want each piece of our page to be and what order to
show it

## What is CSS?
### **C**ascading **S**tyle **S**heets
- Works alongside HTML
- Used to style web pages to make them look better
  - Change colo~~u~~rs, position, effects, font sizes etc

``` css
  p {
    aling: center;
  }
  a {
    decoration: none;
  }
  img {
    height: 100px;
    width: 100px;
  }
```
