# Decimal to Binary Converter

A lightweight browser-based tool for converting non-negative decimal integers to binary. Enter a number to see its base-2 representation. Enter `5` to see an animation illustrating how the recursive conversion uses the call stack.

## Use the converter

No installation or build tools are needed:

1. Clone or download this repository.
2. Open `binaryCodeConverter/index.html` in a browser.
3. Enter a non-negative whole number and select **Convert** (or press **Enter**).

## How it works

The converter uses recursion: it repeatedly divides the number by two, then combines the remainders as the recursive calls return. The base cases are `0` and `1`. For the input `5`, the page also displays a timed call stack animation.

## Project files

```text
binaryCodeConverter/
├── index.html   # Converter interface
├── script.js    # Conversion logic and call stack animation
└── styles.css   # Page styling
```

## Built with

- HTML
- CSS
- JavaScript

This project is a small example of number conversion, recursion, and DOM event handling.
