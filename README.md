# Docsy Acend

Additions for the [docsy theme](https://github.com/google/docsy) for [Hugo](https://gohugo.io/), used for [acend](https://acend.ch) training content.
The docsy-acend theme inherites from the docsy theme through Hugos [Theme Components](https://gohugo.io/hugo-modules/theme-components/).

The theme adds the following to the standard docsy theme:

* brand colors scheme and fonts
* logo and favicons

## Installation

To add the docsy, docsy-plus and docsy-acend themes to an existing Hugo project, run the following commands from your project’s root directory:

```sh
git submodule add https://github.com/google/docsy.git themes/docsy
git submodule add https://github.com/acend/docsy-plus.git themes/docsy-plus
git submodule add https://github.com/acend/docsy-acend.git themes/docsy-acend
git submodule update --init --recursive
```

Reference both themes in your configuration, the docsy-acend theme needs to come before docsy.

Example config.toml:

```toml
theme = ["docsy-acend", "docsy-plus", "docsy"]
```
