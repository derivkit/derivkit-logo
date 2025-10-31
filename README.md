# derivkit-logo

A collection of logos for DerivKit.
These have been generated from the included source file, which requires [ConTeXt](https://wiki.contextgarden.net/).

## Generating the PDFs

From the project root directory run
```
context src/logo.tex
```
This generates a single PDF document with a logo per page.
The individual pages can be split using _e.g._ [pdfseparate](https://manpages.debian.org/testing/poppler-utils/pdfseparate.1.en.html).

## Generating the other files

The PDFs above can be converted into SVG and PNG files using tools such as [Inkscape](https://inkscape.org/) and [GIMP](https://www.gimp.org/downloads/).
