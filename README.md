##### CSS Cheats

# Overview
**To improve productivity**!<br> **Time Saver**! <br> **Reusable**!

## What's Inside

- [BackgroundShadow](https://github.com/Ninja-Vikash/css-cheats/blob/main/README.md#backgroundshadow)
- [HoverCards](https://github.com/Ninja-Vikash/css-cheats/blob/main/README.md#hovercard)

***

### BackgroundShadow
Make your background image dim with any color you want!
```html
<div class="background-img">
    <div class="shadow"></div>
</div>
```
```css
.background-img {
    position: relative;
    height: 100vh;
    width: 100%;
    background: url(" ");
    background-size: cover;
    background-position: center;
}
.shadow {
    height: 100%;
    width: 100%;
    position: absolute;
    background-color: #111;
    opacity: 0.8;
}
```
***

### HoverCard
Make your cards with invisible text and show them on hover
```html
<div class="card-container">
    <div class="card">
        <div class="card-overlay"></div>
        <h4 class="card-text">Text.</h4>
    </div>
</div>
```
```css
.card-container {
    margin: auto;
    margin-top: 40px;
    height: 80vh;
    padding: 10px;
    max-width: 80vw;
    background-color: #222;
    border-radius: 10px;
    display: grid;
    place-items: center;
    grid-template-columns: repeat(4, 1fr);
}

.card {
    position: relative;
    height: 240px;
    width: 280px;
    background: url(" ");
    background-size: cover;
    background-position: center;
    display: flex;
    align-items: center;
    justify-content: center;
    border-radius: 5px;
}

.card-overlay {
    position: absolute;
    height: 100%;
    width: 100%;
    background: crimson;
    opacity: 0;
    transition: all ease 0.7s;
    border-radius: 5px;
}

.card-text {
    color: white;
    font-size: 24px;
    z-index: 2;
    opacity: 0;
    position: absolute;
    transition: all ease 0.7s;
}

.card:hover .card-overlay {
    background: darkcyan;
    opacity: 0.9;
}
.card:hover .card-text {
    opacity: 1;
}
```

***
### Contribution
This repo is open to collaborate. <br> If you have some interesting designs with html and css.

Make a pull request!

#### Happy Coding🤝!