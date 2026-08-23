# @sektek/generator-test

Yeoman-test helpers shared across every `@sektek` generator package's specs.

Thin wrapper around `yeoman-test`, exporting a shared `helper` (a `YeomanTest` instance) and
re-exporting `result`. Specs run generators under test through this `helper` rather than
`yeoman-test` directly, so every `@sektek` generator package's test suite stays consistent.

## Installation

```sh
npm install --save-dev @sektek/generator-test
```
