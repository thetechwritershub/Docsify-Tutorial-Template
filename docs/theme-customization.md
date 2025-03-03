# Theme Customization

Docsify provides several options to customize the look and feel of your documentation using themes. 

## Using Built-in Themes

Docsify comes with pre-built themes that you can implement with minimal configuration. Add any of these theme style sheets in your index.html

```html
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/vue.css">
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/buble.css">
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/dark.css">
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/pure.css">
<link rel="stylesheet" href="//cdn.jsdelivr.net/npm/docsify/themes/dolphin.css">
```

## Custom Styling With CSS
For more control over your documentation's appearance, you can create a custom CSS file to override Docsify's default styles:

Create a custom.css file in your docs folder:

```css
body {
  font-family: Arial, sans-serif;
  background-color: #f9f9f9;
}
```
Link your custom CSS in the index.html file:

```html
<link rel="stylesheet" href="custom.css">
```

## Third-party Themes

Docsify also supports third-party themes and custom modifications. You can check them out [here](https://jhildenbiddle.github.io/docsify-themeable/#/themes)