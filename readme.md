# Sass

## History

- Founder: Designed by Hampton Catlin and developed by Natalie Weizenbaum
- First appeared: November 28, 2006
- Stable release: July 7, 2022
- Story: After its initial versions, Weizenbaum and Chris Eppstein have continued to extend Sass with SassScript, a scripting language used in Sass files
- Goals: Make css development easier
- Stands for: Syntactically awesome style sheets

---

## Definition

Sass is a preprocessor scripting language that is interpreted or compiled into Cascading Style Sheets (CSS). SassScript is the scripting language itself.

---

## file extensions

.sass - .scss

---

## VSCode extension

- Live Sass Compiler(Glenn marks)

---

## Settings up development environment

``` "liveSassCompile.settings.formats": [{ "format": "compressed", "extensionName": ".min.css", "savePath": "/css/" }], "liveSassCompile.settings.generateMap": false ```

---

## Variables

$white-color: #fff

---

## Nesting

.nav {
    &__list {}
    &__item {}
    &__link {}
}

---

## Partial file

_nav.scss

---

## Directives

- @forward
- @use

---

## Collection

- List
- Map

---

## Loops

- for in
- each

---

## Make decision statements

- if else
- switch case

---

## function

@function set-text-color($color) {}

---

## mixin

@mixin set-background-color($color) {}

---

## sass build-in lib
