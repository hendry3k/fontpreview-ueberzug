`fontpreview-ueberzug` is a POSIX shell script to preview all fonts installed on system in `fzf` with `ueberzug`. It is inspired by [fontpreview](https://github.com/sdushantha/fontpreview) project while most of the code are completely rewritten here.

![](./demo.gif)

## Dependencies

- `fzf`
- `imagemagick`
- `ueberzug`
- `fontconfig`

## Usage

```
Usage: fontpreview [-h] [-s FONT_SIZE] [-b BG_COLOR] [-f FG_COLOR] [-t PREVIEW_TEXT]

Font preview with ueberzug and fzf

Options:
   -h show this help message and exit
   -s font size ($FONT_SIZE)
   -b background color ($BG_COLOR)
   -f foreground color ($FG_COLOR)
   -t preview text
```

## Configure

This script makes use of some of the environment variables:

- `FONTPREVIEW_FONT_SIZE`: Font size
- `FONTPREVIEW_BG_COLOR`: Background color
- `FONTPREVIEW_FG_COLOR`: Foreground color
- `FONTPREVIEW_PREVIEW_TEXT`: Preview text to display
