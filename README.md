# Frontend Mentor - Profile card component

![Design preview for the Profile card component coding challenge](./design/desktop-preview.jpg)

### What I learned
1. How to float an image in between sections.
```css
.hero {
    position: relative;
}
.profile img {
    border: 5px solid #fff;
    border-radius: 50%;
    width: var(--PROFILE-WIDTH);
}
.profile {
    position: absolute;
    bottom: calc(0px - var(--PROFILE-WIDTH)/2);
    left: calc(var(--CARD-WIDTH)/2 - var(--PROFILE-WIDTH)/2);
}
```

2. How to control multiple background images.
```css
body {
    background-color: var(--BODY-BGCOLOR);
    background-image: url("../images/bg-pattern-top.svg"), url("../images/bg-pattern-bottom.svg");
    background-repeat: no-repeat;
    background-position: top -74vh right calc(100vw/2), bottom -86vh left calc(100vw/2);
}
```

3. Use CSS calc() function.