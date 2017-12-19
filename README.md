# Modern front-end in Rails

Project to experiment. Say no to Turbolinks, no to Sprockets, no to coffeescript.

The idea is to have separate `frontend` folder for front-end developers and to have css, js and erb files together in the same folder.

## What's included?

* Webpack
* [PostCSS](http://postcss.org) - [36.4 times faster than SASS](https://github.com/postcss/benchmark)
    * Includes [cssnext features](http://cssnext.io/features/) out of the box
* [Normalize.css](https://github.com/necolas/normalize.css/) - A collection of HTML element and attribute style-normalizations
* [ESLint](https://eslint.org) - The pluggable linting utility for JavaScript and JSX
* [Stylelint](https://stylelint.io) - A mighty, modern CSS linter and fixer that helps you avoid errors and enforce consistent conventions in your stylesheets.
* Rails 5.1

## Features

* Automatic page update without refresh after modifying frontend code.
* All staged files will be examined for errors and reformatted automatically with each commit.

## Code Style

* [Prettier](https://prettier.io) - Opinionated Code Formatter. (Alternative would be [Standard](https://standardjs.com))
* [Airbnb javascript style guide](https://github.com/airbnb/javascript)
* [stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard) - Turns on additional rules to enforce the common stylistic conventions found within a handful of CSS styleguides, including: [The Idiomatic CSS Principles](https://github.com/necolas/idiomatic-css),
[GitHub's PrimerCSS Guidelines](http://primercss.io/guidelines/#scss),
[Google's CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#CSS_Formatting_Rules), [Airbnb's Styleguide](https://github.com/airbnb/css#css), and [@mdo's Code Guide](http://codeguide.co/#css).
