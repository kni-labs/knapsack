# Knapsack
A handy bag of Sass mixins and utilities, and the Sass little brother to Stylus's [Axis](http://www.github.com/jenius/axis/) Library.

Knapsack only provides pure css as defined by the w3c spec any browser prefixing  can and should be applied by [auto-prefixer] ([https://github.com/postcss/autoprefixer](https://github.com/postcss/autoprefixer)).

This library is in early development and new mixins will be added quickly,  but for the most part backwards compatibility _should not_ be an issue.

## Installation
- With npm: `npm install knapsack`
- With bower: `bower install knapsack`
- import `knapsack/index` into your css pipeline

## Documentation
Full documentation is [**here**](http://kni-labs.github.io/knapsack/).

## Codepen Sandbox
Experiment with the latest version of Knapsack [on Codepen](http://codepen.io/dbox/pen/zveWGg).

## Contributing
1. Clone/fork the repo:
2. Install dependencies:  `npm install`
3. Install linter: `gem install scss-lint`
4. Add/edit scss in `/knapsack`
5. Add comments to code following [Sassdoc format](http://sassdoc.com/annotations/)
6. Run linter: `scss-lint knapsack -c .scss-style.yml`
7. Create pull request

(Publishing instructions for contributors [here](https://gist.github.com/dbox/57a572101658659ce120))

## Credits
Several mixins ported and adapted from the incredible [Axis Stylus Library](http://www.github.com/jenius/axis/) and a resets are from [scut](https://github.com/davidtheclark/scut).
