A Toasty theme for your hugo website
====================================

### Installing ###

```bash
git submodule add https://github.com/5paceToast/Hugo-Toasty themes/toasty
git submodule init
git submodule update
```

In the future, you can get updates by updating the submodule:

```bash
git submodule update --remote themes/toasty
```

### Configuration ###

Toasty can be configured using the following:

- params.author: The author name, used in the landing page and the footer.
- params.description: The blog's description, used in the landing page.
- params.font: The primary text font, defaults to Roboto. Must be a valid google font.
- params.codefont: The font used for code blocks. Must be a valig google font.
- params.color: Used mostly for link on-hovers, including SVGs. Default: #33C3F0.
- params.herocol: Used to determine the background color of the hero banner on the landing page. Default: #00D1B2.

- menus.main: Each entry here will be on the left side.
- menus.right: Each entry here will be on the right side.

Note: menu entries can have a name (this will display text) and/or an identifier (this must match a font awesome code, and will add an icon to the entry).

### Syntax Highlighting ###
Just `params.PygmentsCodeFences = true`. There is no reason to torture your website's visitors.
