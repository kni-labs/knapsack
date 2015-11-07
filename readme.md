# Knapsack
A handy bag of Sass mixins and utilities, and the Sass little brother to Stylus's [Axis](http://www.github.com/jenius/axis/) Library.

Knapsack only provides pure css as defined by the w3c spec any browser prefixing  can and should be applied by [auto-prefixer] ([https://github.com/postcss/autoprefixer](https://github.com/postcss/autoprefixer)).

This library is in early development and new mixins will be added quickly,  but for the most part backwards compatibility _should not_ be an issue.

## Installation
- With npm: `npm install knapsack`
- With bower: `bower install knapsack`
- import `knapsack/index` into your css pipeline

## Documentation
Full documenation is [**here**](http://kni-labs.github.io/knapsack/).

## Contributing
### Linting / Testing
Scss Linting is provided by [**scss-lint**] ([https://github.com/brigade/scss-lint](https://github.com/brigade/scss-lint)). Let's keep that code tidy.
- Install: `gem install scss-lint`
- Run the test: `scss-lint knapsack -c .scss-style.yml`

### Publish Docs
All mixins/functions need to be formatted for [Sassdoc] ([http://sassdoc.com/annotations/](http://sassdoc.com/annotations/)) so that the [docs] ([http://kni-labs.github.io/knapsack/](http://kni-labs.github.io/knapsack/)) can be auto-generated. To update docs: `npm install` `sassdocify knapsack` `cd .pages && git push -uf origin gh-pages`

## Credits
Several mixins ported and adapted from the incredible [Axis Stylus Library](http://www.github.com/jenius/axis/) and a resets are from [scut](https://github.com/davidtheclark/scut).
