*This repository is a mirror of the [component](http://component.io) module [yields/svg-create](http://github.com/yields/svg-create). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-svg-create`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# svg-create

  Create SVG elements

## Installation

  Install with [component(1)](http://component.io):

    $ component install yields/svg-create

## API

#### create(tag[, length])

Create an array of svg elements of `tag`, with `length` which is defaulted to `1`.

```js
var els = create('text', 8);
assert(8 == els.length);
els.forEach(function(el){
  assert('text' == el.tagName);
});
```

## License

  MIT
