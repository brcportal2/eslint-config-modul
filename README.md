# eslint-config-modul

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-modul-brightgreen.svg)](https://github.com/brcportal2/eslint-config-modul)

An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for JavaScript Modul Style

## Install

```bash
yarn add ssh://git@github.com/brcportal2/eslint-config-modul
```

.eslintrc:
```
{
  "extends": "modul"
}
```

## Rules

Based on [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) with some differences:

- `eol-last` - disabled
- `func-names` - disabled
- `spaces-comment` - disabled
- `import/prefer-default-export` - disabled
- `class-methods-use-this` - disabled
- `indent` - set to 4 spaces
- `react/jsx-indent` - set to 4 spaces
- `react/jsx-indent-props` - set to 4 spaces
- `react/require-default-props` - disabled
- `react/jsx-one-expression-per-line` - disabled
- `jsx-a11y/anchor-has-content` - disabled
- `jsx-a11y/click-events-have-key-events` - disabled
- `jsx-a11y/no-static-element-interactions` - disabled
- `jsx-a11y/anchor-is-valid` - disabled