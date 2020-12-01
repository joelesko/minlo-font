# Minlo

Minlo is a minimal version of the Menlo font that is around 11k per file, versus 150k in the original.

Since Menlo is not available outside of MacOS, this lets you embed it on your website for all users, as long as your code samples are ASCII only (i.e. no need for Latin-1, etc.)


## Glyphs

- ASCII characters
- More distinct backtick (`)
- Unicode 2713 (check)
- Unicode 2715 (multiplication X)


## Format

Only WOFF2 is included, as all modern browsers support it.  


## How to Use It

1. Download the fonts to a directory in your Document Root.
2. Add the fonts to your CSS, like this:

```

@font-face {
    font-family: minlo;
    font-weight: normal;
    src: url(/fonts/Minlo-Regular.woff2);
}

@font-face {
    font-family: minlo;
    font-weight: bold;
    src: url(/fonts/Minlo-Bold.woff2);
}

pre, code {
    font-family: minlo, monospace;
}

```

## License

Menlo is derived from [Bitstream Vera](https://en.wikipedia.org/wiki/Bitstream_Vera), but with minor tweaks made by Apple to a few glyphs (e.g. centered asterisk, more distinct tilde).

From Wikipedia:

> Bitstream Vera was released in 2003 with generous licensing terms and minimal restrictions that are nearly identical to those found in the Open Font License, which was not formalized until two years later. The main restrictions were a prohibition on reselling the fonts as a standalone product (though selling as part of a software package is acceptable), and that any derivative fonts not be distributed under the name "Vera" or use the Bitstream trademark.

See the full [Bitstream Vera License](https://www.fontsquirrel.com/license/Bitstream-Vera-Sans-Mono).



