# BBCode Bundle for Sublime Text

This is a fork of the [TextMate BBCode Bundle][1] by [Ryan Bates][2], Michael Dippery and Grayson Manley.

[1]: https://github.com/gmanley/BBCode.tmbundle
[2]: http://www.rybud.com/


## Installation

### By Package Control

1. Download & Install `Sublime Text 3` (https://www.sublimetext.com/3)
1. Go to the menu `Tools -> Install Package Control`, then,
   wait few seconds until the `Package Control` installation finishes
1. Go to the menu `Preferences -> Package Control`
1. Type `Package Control Add Channel` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, input the following address and press <kbd>Enter</kbd>
   ```
   https://raw.githubusercontent.com/evandrocoan/StudioChannel/master/channel.json
   ```
1. Now, go again to the menu `Preferences -> Package Control`
1. This time type `Package Control Install Package` on the opened quick panel and press <kbd>Enter</kbd>
1. Then, search for `BBCode` and press <kbd>Enter</kbd>

See also:
1. [ITE - Integrated Toolset Environment](https://github.com/evandrocoan/ITE)
1. [Package control docs](https://packagecontrol.io/docs/usage) for details.


## Snippet Keybindings

Use `Cmd+Ctrl` on OS X and `Ctrl+Shift` on other platforms.

    B    Bold
    I    Italic
    C    Color
    @    Size
    W    Wrap (in arbitrary tag)

## Tab Triggers

    code      create code block
    img       create image tag
    url       create URL (link) tag
    1         ordered list block
    *         unordered list block
    -         list item
