# KurobaEx themes

Themes in this repository are used by the in-app theme gallery. 

You can access theme gallery by going to Settings -> Appearance -> Theme -> More themes (They are separated by light/dark type).

# Theme structure updates:

* "back_color_secondary" was introduced in v0.10.x. By default, it's calculated automatically based on "back_color" (either makes it darker or brighter) but it may not look good. So you need to update your themes.

# How to add a new theme into this repository

Color guide can be found here: https://github.com/K1rakishou/KurobaEx-themes/wiki/Dynamic-themes

Make sure the theme json is actually valid! You can check it here: https://jsonformatter.org/ 

Theme file extension is "json". Theme file name must end with the theme type (light or dark), e.g. "example-theme-light.json" if it's a light theme and "example-theme-dark.json" if it's a dark theme. Try not to use whitespaces/unicode symbols in the file name.

1. **Your theme must be unique**! Meaning, if you copy an existing theme and change a couple of colors **IT MOST LIKELY WILL NOT BE ACCEPTED!** Why? Because I don't want to bloat this repository with billions of variants of the Tomorrow theme.
2. Fork this repo.
3. Create a new branch, then create a file with your theme, modify it, commit, push.
