[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/emilbillberg/x-pages)

# x-pages
A lightweight content switcher built with webcomponents.
- [Documentation](https://www.webcomponents.org/element/emilbillberg/x-pages/x-pages)
- [Demo](https://www.webcomponents.org/element/emilbillberg/x-pages/demo/demo/index.html)

## Install
```
bower install --save emilbillberg/x-pages
```

## Example
```
<x-pages selected="[[page]]">
   <div selected="home">Home</div>
   <div selected="about">About</div>
   <div selected="contact">Contact</div>
</x-pages>
```

## Usage
First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

```
polymer serve
```

## Test
Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

```
polymer test
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License
MIT
