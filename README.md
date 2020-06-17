# Style Guid Fundamentals


### What is a style guide
- A book that documents design
- A set of standard and best practice
- A UI library of global styles and components
- A bridge between design and code


### Reference

- [BootStrap](https://getbootstrap.com/docs/4.5/getting-started/introduction/)
- [Marvel](https://marvelapp.com/styleguide/overview/introduction)
- [Atomic Design Methodology](https://atomicdesign.bradfrost.com/chapter-2/)
- [Sass](http://sass.js.org/)

## Requirements

The project's style files use Sass, via [node-sass](https://github.com/sass/node-sass) to watch and compile scss files to CSS, via the following command:

```
node-sass --watch assets/scss/styles.scss assets/css/styles.css
```

To watch and compile the style guide's scss file to CSS, use the following command:

```
node-sass --watch assets/scss/style-guide.scss assets/css/style-guide.css
```