[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/emilbillberg/x-pages)

# x-pages
A simple content switcher

## Install
```
bower install --save emilbillberg/x-pages
```

## Example
<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="x-pages.html">
    <link rel="import" href="demo/x-home.html">
    <link rel="import" href="demo/x-about.html">
    <link rel="import" href="demo/x-contact.html">
    <style>
        x-pages {
            padding: 16px;
        }
    </style>
    <next-code-block></next-code-block>
    <script>
        var pages = document.querySelector("x-pages");
        pages.selected = "home";
        
        document.getElementById("home").addEventListener(`click`, function() {
            pages.selected = "home";
        });

        document.getElementById("about").addEventListener(`click`, function() {
            pages.selected = "about";
        });

        document.getElementById("contact").addEventListener(`click`, function() {
            pages.selected = "contact";
        });
    </script>
  </template>
</custom-element-demo>
```
-->
```html
<button id="home">Home</button>
<button id="about">About</button>
<button id="contact">Contact</button>
<x-pages>
   <x-home pattern="^home$"></x-home>
   <x-about pattern="^about$"></x-about>
   <x-contact pattern="^contact$"></x-contact>
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