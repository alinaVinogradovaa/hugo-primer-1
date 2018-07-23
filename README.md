# The Hugo Primer theme

**Hugo Primer** is a [theme](https://themes.gohugo.io) for the [Hugo](https://gohugo.io) static site generator built around [Primer](https://primer.github.io/), the design system that powers [GitHub](https://github.com).

This theme is oriented toward documentation sites

## Primer versions

Package | Version
:-------|:-------
[`primer`](https://github.com/lucperkins/hugo-primer) | 10.7.0
[`primer-core`](https://github.com/primer/primer/tree/master/modules/primer-core) | 6.10.2
[`primer-product`](https://github.com/primer/primer/blob/master/modules/primer-product) | 5.6.5
[`primer-marketing`](https://github.com/primer/primer/tree/master/modules/primer-marketing) | 6.2.3

## Usage

```bash
hugo new site my-primer-site && cd my-primer-site
git init && mkdir content
git submodule add https://github.com/lucperkins/hugo-primer themes/hugo-primer
echo 'theme = "hugo-primer"' > config.toml
hugo server
```