# NTNU PhD Thesis Template

A LaTeX template for an article-based PhD thesis at the Norwegian University of
Science and Technology (NTNU).

## Attribution and License

This thesis template is based on the original
[`phduio-article-based`](https://github.com/uio-latex/phduio-article-based)
template by Martin Helsø, cited in the thesis as
`\citet{Helsoe_phduioarticlebased_2020}`.

The original template is licensed under the MIT License. Dipendra Pant
customized this template in 2026 for a Doctor of Philosophy thesis at the
Norwegian University of Science and Technology (NTNU), and these customizations
are also licensed under the MIT License.

Copyright @ 2020 [Martin Helsø]

## Acknowledgements

Special thanks to Melissa Yan and Yanzhe Bekkemoen for their support and
encouragement.

## Structure

- `main.tex` is the main thesis file.
- `sections/overview/` contains the overview chapters.
- `sections/publications/` contains the individual paper wrapper files.
- `papers/` contains the included publication PDFs.
- `phduio.cls` and `phdstyle.sty` define the thesis layout and styling.

## Build

Compile the thesis with:

```sh
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

The generated thesis PDF is written to `main.pdf`.

## Preview

The generated PDF from this template can be viewed here:
![Snapshots 1](./main.pdf)
