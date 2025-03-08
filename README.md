# CSS Baseline Reset

This CSS Reset is partially inspired by ["A Modern CSS Reset"](https://piccalil.li/blog/a-modern-css-reset/) and ["A (more) modern CSS Reset"](https://piccalil.li/blog/a-more-modern-css-reset/).

## Opinionated settings
 
- Prefer `box-sizing` inheritance pattern ([src](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/))
- Use `-webkit-font-smoothing: antialiased` (macOS only) ([src](https://dbushell.com/2024/11/05/webkit-font-smoothing/))
- Remove list styles only on ul, ol elements with a `role="list"` ([src](https://www.scottohara.me/blog/2019/01/12/lists-and-safari.html))

## Installation

```
npm install @webfactoryde/baseline-reset
```

## Usage

Use `@import` or `@use` to include this reset in your project's SCSS pipeline.
