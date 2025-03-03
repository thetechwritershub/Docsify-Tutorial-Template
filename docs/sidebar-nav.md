# Adding Navigation with Sidebar
The sidebar provides structured navigation for your documentation.

## Using a Custom Sidebar (_sidebar.md)

To enable the sidebar, add the following to your index.html file:

```html
<script>
  window.$docsify = {
    loadSidebar: true,
    subMaxLevel: 2
  };
</script>
```

Next, create a _sidebar.md file in your docs folder and add the links to your pages.

```markdown
- [Home](README.md)
- [Getting Started](getting-started.md)
- [Features](features.md)
- [Customization](customization.md)
```
> Ensure your markdown files are in the same folder as your _sidebar.md file for it to work.


## Using an Auto-Generated Sidebar (maxLevel)

If you want Docsify to generate a sidebar from a single file, use maxLevel instead. With maxLevel, you do not need to enable the sidebar. This will create a sidebar only from README.md

```html
<script>
  window.$docsify = {
    maxLevel: 3
  };
</script>
```