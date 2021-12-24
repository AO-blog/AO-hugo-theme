# AO - Hugo theme
Base on [archie](https://github.com/athul/archie)

## Feature
- Google Analytics Script
- Callouts
- Tags [fixed]
- Auto Dark Mode(based on system theme)
- Dark/Light Mode toggle
- tl:dr; frontamatter
- Cache busting for CSS files
- LaTeX
- Pdf display
- Music Youtube Bilibili Dplayer Aplayer 

## Writing Posts
Create a new `.md` file in the *content/posts* folder
```yml
---
title: Title of the post
description:
date:
tldr: (optional)
draft: true/false (optional)
tags: [tag names] (optional)
---
```

## Credits

Base on [archie](https://github.com/athul/archie) and Licensed under MIT License

----

## Config Options

### Custom CSS
Custom CSS files can be included though the `customcss` config parameter.

Note: CSS files should be placed under the `assets` directory e.g. `assets/css/first.css`.

```toml
[params]
	customcss = ["css/first.css", "css/second.css"]
```
