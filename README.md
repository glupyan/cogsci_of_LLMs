# Cognitive Science of Large Language Models — Module-free Hugo/blogdown Site

This site is configured to **avoid all Hugo Module and theme conflicts** by providing site-local layouts under `/layouts` and **no external theme**.

## What changed
- Removed all `module:` imports from config.
- No `theme:` set; site-local templates provide basic styling/layout.
- **Schedule**: Assignments section removed.
- Course title and instructor updated.

## Build locally (R)
```r
install.packages("blogdown")
blogdown::install_hugo(version = "0.125.7", extended = TRUE)
blogdown::build_site()
blogdown::serve_site()
```

## Deploy on Netlify
`netlify.toml` sets the Hugo version and build command.
