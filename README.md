# minimal-firefox

### Install

You can install  minimal functional fox through the following steps:

1. Locate your Firefox user directory. You should be able to find it by navigating to `/home/.mozilla/firefox/` and looking for a directory ending with the world `.default-release`.
2. Within your Firefox user directory, locate the `chrome` directory, if one does not already exist you can simply go ahead and create it yourself.
3. Download the contents of this repository, and copy *all* the files to the chrome directory within your Firefox user directory.

After installation, restart Firefox to see the effects.

------

## Customizing

You can easily tweak the theme by changing the relevant CSS variables, starting with `--mff-` located within the :root section at the top of the `userChrome.css` file.

```css
 :root {
     /* Minimal Functional Fox variables*/
     --mff-bg: #293241;
     --mff-icon-color: #e0fbfc;
     --mff-nav-toolbar-padding: 8px;
     /*
     ...
     ...
     ...
     */
}
```

