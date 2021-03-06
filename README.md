This is a fork of [emmet-mode](https://github.com/smihica/emmet-mode) for personal use.

## Changelogs

### 1.2.3 (31 Jan 2019)

* Add personal CSS snippets
* Rename React Native syntax to JSS syntax. Run `emmet-toggle-jss-syntax` to enable/disabled JSS syntax completion.

### 1.2.2 (28 Nov 2018)

* Removed Sass syntax support, and replaced with SCSS syntax support
* Updated CSS snippets, and added SCSS snippets (strong opinionated)
* Removed preferences.el and snippets.el two generated files from repo

### 1.2.1 (20 June 2018)

* merge upstream [#95](https://github.com/smihica/emmet-mode/pull/95)
* merge upstream [#102](https://github.com/smihica/emmet-mode/pull/102)

### 1.2.0

* Updated CSS snippets to the latest [emmet CSS snippets](https://github.com/emmetio/emmet/blob/master/lib/snippets.json).
* Removed some rarely used CSS snippets.
* Removed the `:` from CSS abbrev, e.g. `d:b` is changed to `db` to trigger `display: block;`.
* Removed zero units, e.g. `border-with: 0px;` is changed to `border-width: 0;`.
* Added React Native CSS syntax support, e.g. `margin-top: 10px;` is changed to `marginTop: 10,`. ~~Run `emmet-toggle-rn-css-syntax` to enable React Native CSS syntax.~~
