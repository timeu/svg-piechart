[![Build Status](https://travis-ci.org/timeu/svg-piechart.svg?branch=master)](https://travis-ci.org/timeu/svg-piechart)

# &lt;svg-piechart&gt;

> A web-component to draw a piechart using Polymer and SVG.

## Demo
> [Check it live](https://www.webcomponents.org/element/timeu/svg-piechart).

## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install --save svg-piechart
```

Or [download as ZIP](https://github.com/timeu/svg-piechart/archive/master.zip).

## Usage

1. Import Web Components' polyfill:

  ```html
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
  ```

2. Import Custom Element:

  ```html
<link rel="import" href="../svg-piechart/svg-piechart.html">
  ```

3. Start using it!

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="svg-piechart.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
  <svg-piechart size="250" data="[10,20,50,20]"></svg-piechart>
```


## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

Check [Release](https://github.com/timeu/svg-piechart/releases) list.

## License

[MIT License](http://timeu.mit-license.org/) © Ümit Seren
