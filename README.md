# Atomic components: test

Component for structuring tests, heavily inspired by [SUIT CSS](https://github.com/suitcss).

Read more about [Atomic framework](https://github.com/atomic-css/atomic).

## Installation

* [__Bower:__](http://bower.io)
 `bower install --save atomic-css-components-test`
* [__Component(1):__](http://component.io)
 `component install atomic-css/components-test`
* __Download:__
  [zip](https://github.com/atomic-css/components-test/zipball/master),
  [tar.gz](https://github.com/atomic-css/components-test/tarball/master)
* __Git:__ `git clone https://github.com/atomic-css/components-test.git`

## Available classes

* `Test` - core button component

## Usage

The `Test` component is useful for structuring tests of other components and utilities.
It mimics JavaScript's `describe` and `it` blocks.

```html
<div class="Test">
  <ul class="Test-support">
    <li class="Test-browser Test-browser--chrome">10+</li>
    ...
  </ul>

  <h2 class="Test-describe">.ComponentName</h2>

  <h3 class="Test-it [Test-it--success|Test-it--error]">Should do something.</h3>

  <p>The test itself</p>
</div>
```

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+