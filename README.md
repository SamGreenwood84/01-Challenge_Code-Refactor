# # 01-Challenge_Code-Refactor
**Week 01 Challenge-HTML CSS Git Challenge: Code Refactor**
License: MIT LICENSE

**Description:**
Refactor existing code to make the site more accessible and organized.

**Improved code by:**

Changing the head title to: **"Accessibility for Online Marketing"**
```htm
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Accessibility for Online Marketing</title>
</head>
```

Improved Webpage accessibility standards by adding:
**alt attributes to images.**
***example:***
```htm
<img src="./assets/images/brand-awareness.png" alt="Brand Awareness">
```

Added Semantic HTML Elements:
**header, nav, main, section, article and footer.** 
Code Reference: [W3Schools](https://www.w3schools.com/html/html5_semantic_elements.asp)

Organized content and benefits section by adding;
**.flex-containers**

Sylized by organizing content using: 
**margins, padding, etc.**

Code Reference: [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/CSS/flex-direction)
```css
.flex-container {
    display: flex;
    justify-content: space-around;
}
.content {
    display: flex;
    flex-direction: column;
}
.benefits {
    display: flex;
    flex-direction: column;
}
```
Changed headers to sequential order and organized CSS
***< h1, h2, h3, h4 >**

Hid Footer as per Mockup; Using hidden: See Below;

Code Reference: [W3Schools](https://www.w3schools.com/tags/tryit.asp?filename=tryhtml5_global_hidden)
```htm
<footer hidden>
        <h4>Made with ❤️️ by Horiseon</h4>
        <p>
            &copy; 2023 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
```
To clone the repository & use refactored code:

**Git Hub Repo:** git@github.com:SamGreenwood84/01-Challenge_Code-Refactor.git

