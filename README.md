# unit-synonyms-amount-of-substance

[![Build Status](https://travis-ci.org/javiercejudo/unit-synonyms-amount-of-substance.svg)](https://travis-ci.org/javiercejudo/unit-synonyms-amount-of-substance)
[![Coverage Status](https://coveralls.io/repos/javiercejudo/unit-synonyms-amount-of-substance/badge.svg?branch=master)](https://coveralls.io/r/javiercejudo/unit-synonyms-amount-of-substance?branch=master)
[![Code Climate](https://codeclimate.com/github/javiercejudo/unit-synonyms-amount-of-substance/badges/gpa.svg)](https://codeclimate.com/github/javiercejudo/unit-synonyms-amount-of-substance)

Amount of substance units synonyms

## Install

    npm i unit-synonyms-amount-of-substance

## Units

- [Mole](https://en.wikipedia.org/wiki/Mole_(unit))
- [Pound-mole](https://en.wikipedia.org/wiki/Mole_(unit)#Other_units_called_.22mole.22)

## Usage

```js
var synonyms = require('unit-synonyms-amount-of-substance').synonyms;

synonyms['mol']; // => mole
synonyms['pound moles']; // => poundMole
```

## Related projects

- [linear-presets](https://github.com/javiercejudo/linear-presets): linear presets for common units.
- [linear-converter](https://github.com/javiercejudo/linear-converter): flexible linear converter.
