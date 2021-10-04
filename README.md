# Assignment 2
This assignment focuses on multiple learning goals:
* Strengthening of your HTML and CSS knowledge
* Creating your own responsive "grid" system
* Introduction of NPM as a package manager
* Introduction of SCSS to work more comfortably with stylesheets

## Level 1 - Grid
Have a look at `index.html`. You will find a very basic markup with a few headlines, paragraphs 
and divs that have custom classes like `row` or `col-100`. 

The first task is to create a very basic 4-column grid system: 
```text
row: container of multiple columns in one row
col-100: 100%
col-50: 50%
col-25: 25%
```

_Note: columns should only be valid *inside* a `.row`!_
Solve the task by only using CSS without any changes to the markup.

## Level 2 - Responsiveness
This time, you need to change the markup! 
Implement 3 breakpoints: 
```
small: 0-500
medium: 501-1000
large: 1001-*
```

* Add classes to the columns so that on *medium*: col-100 and col-50 are full-width and col-25 is half the page width.
* Add classes to the columns so that on *small*: col-100, col-50, and col-25 are all full-width.
* Make the images resize with the width of their column.
* Add padding/margin to all rows and columns, so you have an aesthetic look and nice spacing.

## Level 3 - Node Package Manager (npm)

* Read through the NPM beginners guide: https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/
* Initialize `npm` in your project
* Add `node_modules/` to the git-ignored files (don't commit anything inside `node_modules`)
* Install the `sass` package to your repository (https://www.npmjs.com/package/sass)
* Commit the `package.json` and `package.lock` files to the repository

## Level 4 - SCSS
* Read about how to use SASS/SCSS, e.g.:
    * https://weareneon.com/blog/a-beginners-guide-to-scss
    * https://www.code-boost.com/beginners-guide-to-scss/
    * https://sass-lang.com/guide
    * https://sass-lang.com/documentation/cli/dart-sass
* Move your `css/styles.css` code to `scss/styles.scss` and use the nesting features of SCSS on your stylesheets
* Compile your `scss/styles.scss` to `css/styles.css` by running it on the CLI & commit the files

_Hint: for running sass on the CLI, you either need to install it globally or run it
from `node_modules/.bin/sass <input> <output>`_

_*Bonus: Try out the `@import` and `$variable` features of SCSS to change themes (i.e. color schemes) of your project*_