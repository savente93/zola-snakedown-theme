# Snakedown Docs 

![Snakedown logo: a snake with a business tie and a bolwer hat next to the word "Snakedown" in an old school type writer font](static/snek-banner.webp)

A Batteries included [Zola](https://www.getzola.org) theme to use with [Snakedown](https://github.com/aslowwriter/snakedown) for Python documentation.

Snakedown is a tool to extract signature and docstrings from your Python project and automatically generate an API documentation so that you can use it in your favourite static site generator (in this case Zola) to host your documentation. 

While you can use it perfrectly fine on it's own, it is built to be used and compatible with the output of Snakedown. It is developed along side that tool, and this theme's features will be kept in sync with that tool. 

## Features

As Snakedown and this theme are both still quite young, features will continue to be added as Snakedown is developed, but currently the theme has the following features: 

- Navbar at the top for main sections of your docs/site, with active marker for current page section
- No JS
- Responsive design with Bootstrap CSS
- Side bar for navigating pages in current section
- Configurable favicon and logo in the Navbar options 
- Defaults designed to work out of the box, but be customizable

## Installation

First clone this repo into your themes from the root of your site: 

```bash
$ git clone https://github.com/aslowwriter/zola-snakedown-theme.git themes/snakedown

```

Then set it as the used theme in your website's `config.toml`:

```toml
theme = "snakedown"
```
## Usage

This works like any other zola site. The direct subsections of the root section will appear in the top navbar. 

When on a page, or section the sidebar will display the pages in that section. Currently this is not recursively.



## Customisation options

TBC

## Contributing

I'd very much appreciate feedback, feature requests and bug reports. Please report those [in the issue tracker](https://github.com/aslowwriter/zola-snakedown-theme/issues). If you are reporting a bug please include a screenshot of the issue for reference (if possible and appropriate). PRs are also welcome though I'd advise you to reach out first and discuss your ideas to avoid wasted work.


## Special Thanks
Thank you to:
- [@ghostcatte](https://www.patreon.com/c/ghostcatte/posts?vanity=ghostcatte) for the snek logo.
- [the PyData Community](https://pydata-sphinx-theme.readthedocs.io/en/stable/) as serving for the template (pun intended) for this theme
- [Astigmatic](https://fonts.google.com/specimen/Special+Elite) for desining the Special Elite font I used in the banner image above

