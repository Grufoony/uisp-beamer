# UISP Nuoto Beamer theme

A Beamer theme inspired by the [CIS Group Princeton Beamer template](!https://github.com/cisgroup/princeton-beamer) and adapted to the visual language of UISP / UISP Nuoto.

## Setup

Place the theme `.sty` files in the same directory as your presentation and put your own `logo.png` there.

Compile with:

```bash
pdflatex main.tex
```

## Title page

The title page uses a strong UISP-green institutional panel on the left, a clean white content area on the right with a cartoon from `cartoon.png`. The UISP logo is loaded from `logo.png` and `logo-white.png`.

The event label is intentionally separated from the logo so that longer event names do not overlap it.

## Example

See `main.tex`.
