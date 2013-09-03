# Bits.sass utilities: responsive offset

Responsive superset of space utilities.

See [Bits.sass utils-offset](https://github.com/bits-sass/utils-offset) for more
about original utilities.

Read more about [Bits.sass toolkit](https://github.com/bits-sass/bits.sass).

## Installation

* __Bower:__ `bower install --save bits-sass-responsive-utils-offset`
* __Download:__ [zip](https://github.com/bits-sass/responsive-utils-offset/zipball/master),
  [tar.gz](https://github.com/bits-sass/responsive-utils-offset/tarball/master)
* __Git:__ `git clone https://github.com/bits-sass/responsive-utils-offset.git`

## Available SASS variables

* `bits-utils-ns` - utilities namespace, defaults to 'bits-'
* `bits-responsive-offset-columns` - list of column variations, used by
  `u-beforeXofY` and `u-afterXofY`

## Available utility classes

* `v[n]-u-beforeXofY` (adjustable) - specifies the proportional offset before
  an object on `n` breakpoint
* `v[n]-u-afterXofY` (adjustable) - specifies the proportional offset after
  an object on `n` breakpoint

## Requirements

* Sass 3.2+

## Browser support

* Google Chrome (latest)
* Opera (latest)
* Firefox 4+
* Safari 5+
* Internet Explorer 9+ (IE 8 requires a build step)