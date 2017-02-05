# Color Cards

### [View Demo](http://derekbtw.com/color-cards/)

## Usage

Add the CSS found in [/dist/color-cards.css](https://github.com/derekbtw/color-cards/dist/color-cards.css) to your project.

-or-

You can use the RawGit CDN

<details>
<summary>CDN URL</summary>
```html
https://cdn.rawgit.com/derekbtw/color-cards/56c92dd7/dist/color-cards.css
```
</details>

<details>
<summary>CDN with link tag</summary>
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/derekbtw/color-cards/56c92dd7/dist/color-cards.css">
```
</details>

### Markup

Since Color Cards use flexbox, it's easy to use 1-5 different colors on each card. However, using more than 5 will need a little customization to your CSS. The cards must be inside ```.flex-grid``` - here's an example:

```html
  <div class="flex-grid">
  
    <div class="palette" id="01">
      <div class="wrapper">
        <div class="colors">
          <div class="color" style="background: #F9ED69"><span>#F9ED69</span></div>
          <div class="color" style="background: #F08A5D"><span>#F08A5D</span></div>
          <div class="color" style="background: #B83B5E"><span>#B83B5E</span></div>
          <div class="color" style="background: #6A2C70"><span>#6A2C70</span></div>
        </div>
        <footer>First</footer>
      </div>
    </div>
    ...
  </div>
```

As you can probably see, it's extremely easy to add new cards. There's no messing with any CSS files, just change the color values right in the inline styles using HTML. Also, since Color Cards utilize flexbox, you can simply add as many cards as you want and flexbox takes care of the spacing.

The font used on the demo is called Reenie Beanie. Add the Google Font library to your page:
```html
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Reenie+Beanie">
```
```css
.palette {
  font-family: "Reenie Beanie", sans-serif;
}
```

If you'd like to contribute to the project, PLEASE DO!
