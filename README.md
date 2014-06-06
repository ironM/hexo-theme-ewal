# Hexo theme based on Twitter Bootstrap Theme using LESS

See [Philipps blog](www.philippkeller.com) for a demo.

### Features of this theme

- optimized for readability (~70 characters per line, enough margin between body and sidebar)
- done for offline writing: all css and js files are part of the theme, the blog looks the same online as offline
- ported from the [docpad theme of Erv Walter](https://github.com/ervwalter/ewalnet-docpad)
- based on twitter bootstrap using LESS and variables.css ⇒ colors should be very easy to customize
- addthis support
- about me is a slick bootstrap carousel
- custom javascripts per page (add them in YAML front matter with scripts: …)

### custom javascript per page

If you need to include a custom javascript on one of your pages add this to front matter:

```
scripts:
- /scripts/jquery.dataTables.min.js
- /scripts/table_scroll.js
```

### install

    npm install hexo-renderer-less --save
	git clone git://github.com/philippkeller/hexo-theme-ewal.git themes/ewal

## Update

Execute the following command to update:

```
cd themes/twbootstrap
git pull
```
