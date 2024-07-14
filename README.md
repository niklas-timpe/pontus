# pontus

Minimalistic blog theme powered by [Zola](https://getzola.org).

<sub><sup>Named after the greek god of the sea</sup></sub>

<details open>
  <summary>Dark theme</summary>

  ![blog-dark](./screenshot-dark.png)
</details>

<details>
  <summary>Light theme</summary>

![blog-light](./screenshot.png)
</details>

## Features

- [X] Pagination
- [X] Themes (light, dark, auto)
- [X] Projects page
- [X] Analytics using [GoatCounter](https://www.goatcounter.com/) / [Umami](https://umami.is/)
- [x] Social Links
- [x] MathJax Rendering
- [x] Taxonomies
- [x] Meta Tags For Individual Pages
- [x] Custom homepage
- [x] Comments
- [ ] Search
- [ ] Categories

## Installation

1. Download the theme
```
git submodule add https://github.com/niklas-timpe/pontus themes/pontus
```

2. Add the following to the top of your `config.toml`

```toml
theme = "pontus"
taxonomies = [{ name = "tags" }]

[extra]
theme = "auto"
socials = [
  # Configure socials here
]
menu = [
  # Configure menu bar here
]

```

3. Copy the example content

```
cp -r themes/pontus/content/* content/
```

## Configuration

You can find all the configuration options [here](./content/posts/configuration.md)

## References

This theme is a fork of [apollo](https://github.com/not-matthias/apollo).
