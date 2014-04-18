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

* `Test` - core test component
* `Test-title` - test title
* `Test-describe` - the 'describe' block
* `Test-it` - the 'it' block
* `Test-it--success` - successfull 'it' block
* `Test-it--error` - errorneous 'it' block
* `Test-run` - the 'it' block
* `Test-support` - browser support wrapper
* `Test-browser` - browser and its version
* `Test-browser--android` - Android
* `Test-browser--blackberry` - Blackberry
* `Test-browser--chrome` - Chrome
* `Test-browser--chromeCanary` - Chrome Canary
* `Test-browser--firefox` - Firefox
* `Test-browser--firefoxNightly` - Firefox Nightly
* `Test-browser--ie` - Internet Explorer
* `Test-browser--ieMobile` - IE Mobile
* `Test-browser--opera` - Opera
* `Test-browser--safari` - Safari
* `Test-browser--safariIos` - iOS Safari

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

  <div class="Test-run">
    <p>The test itself</p>
  </div>
</div>
```

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 8+