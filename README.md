# NetBeans Color Codes Preview Plugin

This plugin shows a color codes preview in an editor's sidebar.

![screenshot](https://dl.dropboxusercontent.com/u/10953443/netbeans/color-codes-preview/netbeans-color-codes-preview-screenshot.png)

## Disable/Enable

Check/Uncheck `View > Show Colors`

## Downloads

- https://github.com/junichi11/netbeans-color-codes-preview/releases

## Supported color patterns

- Hex color code (e.g. #fff #000000)
- Css rgb/rgba values (e.g. rgb(0, 0, 0), rgb(50%, 0%, 100%), rgba(255,255,255, 0.8))
- Css hsl/hsla values (e.g. hsl(0, 100%, 50%), hsla(120, 100%, 50%, 0.5))

## Multiple colors

- Show top two colors in a sidebar if there are multiple colors in a line.
- If you want to check all colors, please click a specific rectangle. They will be shown as a list.

## Change a color using the color chooser

- Click a colored rectangle
- Click a color value of a list
- Select a new color in the color chooser
- An old color value will be changed to new one with the same format

## Options

Tools > Options > Miscellaneous > Color Codes Preview

### Regex for enabled mime-types

Default value is `^text/(x-)?(css|less|sass|scss)$`.
If you would like to disable/enable some mime-types, please change the default regex.
This pattern is used when the plugin checks a mime-type.

## NOTE

- Colors may be shown if they are not color codes. e.g. "#feature" contains `#fea`. This plugin recognizes it as a hex color code.
- If you use the GTK Look and Feel, you cannot change an alpha value in the color chooser.
- Hsl or hsla color values may not be changed correctly when you use the color chooser. (There may be 1% errors.)

## License

[Common Development and Distribution License (CDDL) v1.0 and GNU General Public License (GPL) v2](http://netbeans.org/cddl-gplv2.html)
