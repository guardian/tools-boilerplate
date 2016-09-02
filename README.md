# Tools Boilerplate
A *very* basic HTML and CSS (with preprocessors) Boilerplate to keep our tools looking consistent and to save time when they all look the same anyway.

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
