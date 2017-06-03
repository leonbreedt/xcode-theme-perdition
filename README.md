Xcode Theme: Perdition
======================

This is my personal theme for editor colors & fonts in Xcode 8.

It's based on the default Xcode theme, with color cues from the Atom [One Light](https://github.com/atom/one-light-syntax) theme.

# Prerequisites

To get it to look exactly the same, you'll need to download and install my [custom build](https://github.com/leonbreedt/iosevka-term-custom) of the [Iosevka](https://github.com/be5invis/Iosevka) font.

**NOTE**: If you don't tweak the `AppleFontSmoothing` defaults, the font weight
will be on the heavy side.

I use the following to tweak my Xcode font rendering:

```shell
defaults write com.apple.dt.Xcode AppleFontSmoothing -int 0
```

I don't like the setting system-wide, but I want it for my code/terminal
windows.

# Sample

<img src="https://raw.githubusercontent.com/leonbreedt/xcode-theme-perdition/master/Preview.png" alt="Preview" width="556" height="361">
