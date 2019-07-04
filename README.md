# Front-end at VI Company

_All code in any code-base should look like a single person typed it, no matter how many people contributed._

## General

* We highly regard Accessibility and Web Standards.
* We use [Progressive Enhancement](https://www.gov.uk/service-manual/technology/using-progressive-enhancement) as much as possible.
* We support the latest [Evergreen Browsers](#evergreen-browsers) (but often also older browsers, because of the previous points).

## JavaScript (ES2015+)

* Codebase is modular JavaScript ([ES2015+](http://www.ecma-international.org/ecma-262/7.0/)).
* Vanilla is preferred, but developers are free to choose a framework/library to their liking if it substantially improves product maintainability.
* Reusable components (NPM modules) are preferred over [reinvention](https://www.freecodecamp.org/news/how-to-stand-on-shoulders-16e8cfbc127b/).
* Our ES2015+ codebase is transpiled and bundled using [Rollup](https://rollupjs.org/) and [Babel](https://babeljs.io).
* To improve browser compatibility, use [ponyfills](https://github.com/sindresorhus/ponyfill) or polyfills. The former is preferred.
* Code is linted using [ESLint](http://eslint.org), following the rules defined in [VI Company's config](https://www.npmjs.com/package/eslint-config-vi).

## CSS (Sass)

* We write modular Sass using the `SCSS` [syntax](http://www.sass-lang.com/documentation/file.SASS_REFERENCE.html#syntax).
* We use [BEM](https://en.bem.info) for class names.
* Combined with a sprinkle of [SMACSS](https://smacss.com) for states.
* And we follow the [ITCSS](https://www.xfive.co/blog/itcss-scalable-maintainable-css-architecture) approach for our project architecture, along with the [Atomic design](http://atomicdesign.bradfrost.com) methodology for setting up our components.
* We use [Stylelint](http://stylelint.io) and our own [config](https://www.npmjs.com/package/stylelint-config-vi) to lint our Sass code.

### Sass guidelines

* See our [Sass guidelines](SASS.md).

## Tooling

* We use [npm scripts](https://docs.npmjs.com/misc/scripts) for compiling JS, CSS, optimization and other tasks.
* See our [Front-end recipes](https://github.com/vicompany/front-end-recipes).

## Editor plugins

Whether you use [Visual Studio Code](https://code.visualstudio.com), [Sublime Text](https://www.sublimetext.com) or any other editor. You should at least use the following plugins:

* [EditorConfig](http://editorconfig.org)
* [ESLint](http://eslint.org)
* [Stylelint](http://stylelint.io)

## Additional information

### Evergreen Browsers

The term _evergreen browser_ refers to a browser that gets updated automatically to future versions.
Therefore browser versions become less of a focus and, more importantly, new web technology becomes available to users and us developers quicker.

* [The Evergreen Web by Scott Hanselman](http://www.hanselman.com/blog/TheEvergreenWeb.aspx)
* [Evergreen Browsers by Rob Eisenberg](http://eisenbergeffect.bluespire.com/evergreen-browsers/)
