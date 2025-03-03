# Site Configurations

By default, Docsify uses "Document" as the site title. To change it, update the `<title>` tag in `index.html`:

```html
<title> Docsify Demo </title>
```

Next, update the following details in your `<script>` tag. 

```html
<script>
    window.$docsify = {
      name: 'Docsify Demo Site',  // Site name displayed in the sidebar
      repo: 'https://github.com/thetechwritershub', // GitHub repo link
      logo: '', // Custom logo
      themeColor: '#000000' // Primary theme color
    };
</script>
```