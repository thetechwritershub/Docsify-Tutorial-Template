# Setting Up and Customizing Cover Page

Docsify allows you to add a cover page to serve as a welcoming introduction to your documentation.

## Enabling the Cover Page

To enable the cover page, update your `index.html` file:

```html
<script>
  window.$docsify = {
    coverpage: true
  };
</script>
```

Create a _coverpage.md file in the docs folder and add your custom content.

```markdown
<!-- Optional, but you can add your project or brand logo -->
![logo](img/logo.png)

# Docsify Documentation Guide by TechWriters Hub  

> *A lightweight and flexible documentation site generator*  

- 📖 Easy to learn  
- ⚡ Quick setup  
- 🚀 No build process required  

<!-- You can add buttons that direct users to key sections of your documentation -->

[GitHub](https://github.com/thetechwritershub/Docsify-Tutorial-Template)  
[Get Started](README.md)  

```

## Customizing Your Coverpage

By default, the cover page's background color is randomly generated and changes as you refresh. After enabling your coverage, you can make many other customizations to enhance it.


- To use a solid color or an image as the background. Modify your `_coverpage.md` file:

```markdown
<!-- Solid color background -->
![bg](#f0f0f0)

<!-- Background image -->
![bg](img/background.jpg)
```

- Docsify lets you scroll through the cover page to reveal your main documentation content.
  
- To make the cover page take up the full screen on the first load and hide the sidebar and content until the user interacts, use onlyCover:

```html
<script>
  window.$docsify = {
    coverpage: true,
    onlyCover: true
  };
</script>
```

This is what your cover page should look like:

![cover page](img/Cover-page.png)