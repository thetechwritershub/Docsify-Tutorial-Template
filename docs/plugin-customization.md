# Customization Using Plugins

Docsify's plugin ecosystem is a major advantage over other static generators. With a few script additions, you can enhance the overall experience of your site. Here are some essential ones:

## Search Plugin

Search bar to help users quickly find content in your documentation. Add the following script to your index.html:

```html
<script src="//cdn.jsdelivr.net/npm/docsify/lib/plugins/search.min.js"></script>
```

Next, enable search in your configuration

```html
<script>
  window.$docsify = {
    search: 'auto', // Enables search automatically
  };
</script>
```

Optionally, you can choose to configure other search parameters:

```html
<script>
  window.$docsify = {
    search: {
      maxAge: 86400000, // Cache duration in milliseconds (1 day)
      paths: 'auto', // Index all files automatically
      placeholder: 'Search...',
      noData: 'No results!',
      depth: 2, // Limit search to headings up to H2
    }
  };
</script>
```

## Copy to Clipboard Plugin

This plugin adds a copy button to every code block, making it easier for users to copy.

```html
<script src="//cdn.jsdelivr.net/npm/docsify-copy-code/dist/docsify-copy-code.min.js"></script>
```

## Pagination Plugin

This plugin makes navigation between pages easy.

```html
<script src="//cdn.jsdelivr.net/npm/docsify-pagination/dist/docsify-pagination.min.js"></script>
```

Visit the docsify documentation for more plugin options, and for advanced customization, you can create custom plugins to extend Docsify's functionality.