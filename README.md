# Isotope.next

_Filter & sort magical layouts for Next.js_

See [isotope.metafizzy.co](https://isotope.metafizzy.co) for complete docs and demos.

## Install

### Package managers

npm: `npm install isotope-next --save`

Bower: `bower install isotope-next --save`

## License

### Commercial license

If you want to use Isotope to develop commercial sites, themes, projects, and applications, the Commercial license is the appropriate license. With this option, your source code is kept proprietary. Purchase an Isotope Commercial License at [isotope.metafizzy.co](https://isotope.metafizzy.co/#commercial-license)

### Open source license

If you are creating an open source application under a license compatible with the [GNU GPL license v3](https://www.gnu.org/licenses/gpl-3.0.html), you may use Isotope under the terms of the GPLv3.

[Read more about Isotope's license](https://isotope.metafizzy.co/license.html).

## Initialize

With jQuery

``` js
$('.grid').isotope({
  // options...
  itemSelector: '.grid-item',
  masonry: {
    columnWidth: 200
  }
});
```

With vanilla JavaScript

``` js
// vanilla JS
var grid = document.querySelector('.grid');
var iso = new Isotope( grid, {
  // options...
  itemSelector: '.grid-item',
  masonry: {
    columnWidth: 200
  }
});
```

With HTML

Add a `data-isotope` attribute to your element. Options can be set in JSON in the value.

``` html
<div class="grid"
  data-isotope='{ "itemSelector": ".grid-item", "masonry": { "columnWidth": 200 } }'>
  <div class="grid-item"></div>
  <div class="grid-item"></div>
  ...
</div>
```

* * *

By [Metafizzy 🌈🐻](https://metafizzy.co), 2010–2020
