# stylelint-config-bandlab

This package provides BandLab's configuration for [`stylelint`](https://github.com/stylelint/stylelint). Similar to ESLint, stylelint helps enforcing consistent (S)CSS conventions across projects.

## Installation

```sh
npm install --save-dev @bandlab/stylelint-config-bandlab
```

## Usage

Create a `.stylelintrc.yml` configuration file and extends it with `stylelint-config-bandlab`:

```yml
extends: '@bandlab/stylelint-config-bandlab'
```

Lint stylesheets via CLI:

```sh
npm install -g stylelint
stylelint foo/*.css
```

> More details in the [stylelint documentation](https://github.com/stylelint/stylelint#getting-started).
