![Monaco](https://raw.github.com/vjpr/monaco-bold/master/logo.png)

# Monaco Bold

_The Monaco font with a bold variant_

## Examples

**Monaco - Original**

![Monaco](https://raw.github.com/vjpr/monaco-bold/master/Monaco.png)

**MonacoB**

![MonacoB](https://raw.github.com/vjpr/monaco-bold/master/MonacoB/MonacoB.png)

**MonacoB2**

![MonacoB2](https://raw.github.com/vjpr/monaco-bold/master/MonacoB2/MonacoB2.png)

## Motivation

My favorite fixed-width programming font is Monaco 10pts. I develop in IntelliJ on OSX which uses boldness as part of its syntax highlighting. Unfortunately Monaco doesn't include a bold variant. Initially I thought it would be easy to find a replacement font with a bold variant, but I was not happy with any of the replacements. Some replacements I looked at were: Consolas, Inconsolata, Droid Sans Mono and Bitstream Vera Sans Mono.

## The Fonts

I have created three fonts with different weights for the bold variant. You may be asking why I didn't use variants such as Semi-Bold or Extra-Bold. The reason for this is IntelliJ's (and I'm guessing other editors) syntax highlighting doesn't allow creating highlighting rules for font variants other than bold, italic.

- MonacoB - bold (20% transform)
- MonacoBSemi - bolder (30% transform)
- MonacoB2 - boldest (40% transform)

`Monaco.dfont` is the original font from OSX.

## Install

### OSX

Drag-drop `MonacoB/MonacoB.otf` and `MonacoB/MonacoB-Bold.otf` into `Font Book > User` or double-click and select `Install font` from the dialog. Repeat the same for the `MonacoB2` folder.

## How?

The new fonts were created by transforming height and width of each glyph, and modifying the font meta-data to allow it to be installed side-by-side with the system Monaco.

---

The font looks great on OSX - have not tested on Windows.

Hope you like it!