# Tools Boilerplate
A *very* basic HTML and CSS (with preprocessing coutesy of Sass) Boilerplate to keep our tools looking consistent and to save time when they all look the same anyway.

## Development

### Setup
Require Node 6, it's recommended that you use [nvm](https://github.com/creationix/nvm) to help manage versions of Node between projects.

```
nvm use // switches to the correct Node version
npm install // installs dev devDependencies
```

### Building
The only thing that's compiled here is the SCSS/Less. Run `npm run sass` or `npm run less` to compile from the SCSS or Less respectively.

## Use
Pick the preprocessor of your choice, include that in your project and compile it however you like.
The HTML serves as a guide for classnames, as well as semantic HTML and use of a11y roles.

For more info on (very basic) a11y, visit [the a11y project](http://a11yproject.com/)

## Structure and file description
This is *only* intended as a kick-start to your project styles and structure - edit anything and everything as you wish.


```
.
├── assets
|   ├── fonts // font files
|   |── images // all site images
|   └── stylesheets
|       └── scss/less // .scss or .less files
|           |── abstracts // non-compiling files (variables, mixins, etc)
|           |── base // top-level styles (body block, typography, helpers, etc)
|           |── components // Small, generic, reusable blocks (buttons, forms, etc)
|           |── layout // Page specific or larger components
|           └──  vendor // 3rd party styles
└── index.html // Basic HTML structure, open for styles preview

```

## Maintenance
- If you make any style changes/additions, ensure you do it in both Less and Sass
- This is intended to be very basic, nothing too single product focused
