# Repository of Tooling

Resources and tools for modern web production. An opinionated but flexible document.

Useful for me to stash links, probably not useful for you yet.

*Disclaimer: The right tool depends on the project's needs and not just your hipster whims*

## View Structure

[React](https://facebook.github.io/react/) for manipulating the DOM with certainty.


## Cascade-less Styling

CSS has various natural properties that (if untamed) lead to mess and uncertainty. Lack of scoping, specifity conflicts, and dead code problems can be managed with careful component-based naming conventions or view-managed styling.

[CSS Modules](https://github.com/css-modules/css-modules) uses generated classnames so you can write css scoped to your component. Also, its `compose` pattern is much cleaner than SASS's extend. For more info, see this great [guide](http://glenmaddern.com/articles/css-modules).

If you can't use CSS Modules, a naming pattern like [SUIT CSS](http://suitcss.github.io) or BEM will help to constrain specificity and modularise CSS.

[Basscss](http://www.basscss.com) is a different way to work altogether, composing the styling of an element in the class list. With its immutable CSS pattern (no overrides), you can style things quickly and with confidence without leaving your template code.

React lets you manage styling with the same patterns you're used to in actual programming. This means using inline-styles instead of CSS and has tons of benefits. [Radium](http://projects.formidablelabs.com/radium/) makes this a bit nicer.


## Module System


## Pre-processors

Babel for writing modern Javascript irrelevent of browser support.


## Frontend Testing

Tape


## Backend

Ruby on Rails for core logic (or indeed code monoliths).
Elixir/Phoenix is great in theory (so long as you're the only one on the project).
Go is good for services and pipes.
Node is good for isometric web apps.
Meteor is great for when you need magic glue between frontend and backend. Very good for prototyping, great as a backend to React.

## Accessibility
[tota11y](http://khan.github.io/tota11y/)

## Testing / QA
[Naughty strings](https://github.com/minimaxir/big-list-of-naughty-strings/blob/master/blns.txt)

## Prototyping

## Design concepts
[Spacial interfaces](https://medium.com/elepath-exports/spatial-interfaces-886bccc5d1e9)


## Design Inspiration

[CALLTOIDEA](http://www.calltoidea.com)
[Little Big Details](http://littlebigdetails.com)

## Low Fidelity Design Production

Keynote - lends towards simple, flat designs. Easy to demonstrate animations with Magic Move

## Higher Fidelity Design Production

Sketch
