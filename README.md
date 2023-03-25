# jQuery Number Formatter

`jqueryNumberFormatter` is a small and simple jQuery library for formatting numbers as the user types into an input field.

The library adds a thousands separator and decimal separator to the input value, as well as restricts input to valid numbers and decimal places. It also allows real-time formatting of numbers above a thousand, including adding a separator as the user types.

## Getting Started

### Prerequisites

- jQuery library (version 1.7 or higher)

### Installing

1. Download the `jqueryNumberFormatter.js` file and include it in your HTML file after the jQuery library is loaded:

```html
<script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
<script src="jqueryNumberFormatter.js"></script>


Call the numberFormatter function on a valid jQuery object:
```html
$(document).ready(function() {
  $('#myInput').numberFormatter();
});

## Options
The numberFormatter function accepts an optional options object to customize the thousand separator and decimal separator used in the formatted number:

```html
$(document).ready(function() {
  $('#myInput').numberFormatter({
    thousandSeparator: '.',
    decimalSeparator: ','
  });
});

By default, the library uses a comma (,) as the thousand separator and a period (.) as the decimal separator.

Example
You can see an example of the jqueryNumberFormatter library in action by opening the example.html file included in this repository.

Contributing
If you'd like to contribute to this library, please feel free to submit a pull request or open an issue. All contributions are welcome!

License
This library is licensed under the MIT License - see the LICENSE file for details.
