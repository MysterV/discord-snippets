Small, modular CSS snippets to improve tiny bits of Discord app's appearance.
Designed to work with custom Discord clients' custom CSS loaders.

Feel free to incorporate them into a theme if you want, and later let me know so that I can check it out. 🥺


# Installation
In the settings, there should be an option called "Quick CSS" or "Custom CSS".
Once you open the custom CSS editor, you have these options:

#### 1. Pick a CSS snippet and copy its contents directly into the CSS editor
<br>

#### 2. Use a one-liner `@import`, which saves space and ensures you're always up-to-date, using the following format:  
```css
@import url("https://raw.githubusercontent.com/MysterV/discord-snippets/main/css/NAME.css");
```
\* replace `NAME.css` with the name of the snippet you want, e.g.
```css
@import url("https://raw.githubusercontent.com/MysterV/discord-snippets/main/css/auto-hide-sidebar.css");
```
<br>

#### 3. To import ***everything*** at once, use `all.css`:

```css
@import url("https://raw.githubusercontent.com/MysterV/discord-snippets/main/css/all.css");
```



## TODO:
- [ ] add previews
- [ ] remove vc text chat min width (if possible)
- [ ] add a toggle for channel list auto-hide
- [ ] make the server list auto-hide, somehow...
