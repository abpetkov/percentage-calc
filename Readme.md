# Percantage-calc

## Description

Simple percentage calculations.

## Installation

##### Standalone:

```html
<script src="dist/percentage-calc.js"></script>
```

##### NPM:

```shell
$ npm install percentage-calc
```

##### Component:

```shell
$ component install abpetkov/percentage-calc
```

##### Bower:

```shell
$ bower install percentage-calc
```

## Usage

If you're using Node.js or Component, include the script like so:

```js
var percentage = require('percentage-calc');
```

Otherwise, continue with the examples.

## Examples

If you want to calculate how much is a percent of a number, ex. 20% of 100, use the `of` method:

```js
percentage.of(20, 100); // will return 20
```

If you'd like to know what percent of a number is another number, ex. 30 is what percent of 100, use the `from` method:

```js
percentage.from(30, 100); // will return 30
```

## Contact

If you like this and want to see more of my work, share your appreciation by following me in [Twitter](https://twitter.com/abpetkov), [GitHub](https://github.com/abpetkov) or [Dribbble](http://dribbble.com/apetkov).

## License

The MIT License (MIT)

Copyright (c) 2014 Alexander Petkov

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.