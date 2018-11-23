# ReText Themes

## Configurations

ReText stores all of its configuration in a text file: `~/.config/ReText project/ReText.conf`.  
See the [possible configuration options](https://github.com/retext-project/retext/blob/master/configuration.md#color-scheme-setting)

You can change

* the theme of the window, using [Qt stylesheets](http://doc.qt.io/archives/qt-4.8/stylesheet.html).   
  Add `appStyleSheet=/home/YOUR_USERNAME/.config/ReText project/YOUR_FILE.qss` to the configuration file

  <ins>Example (retext.qss)</ins>:

  ```
  QTextEdit {
    color: black;
    background-color: white;
  }
  ```

* the color scheme of the text editor, using a `[ColorScheme]` section in the configuration file

  <ins>Example (ReText.conf)</ins>:

  ```
  [ColorScheme]
  htmlTags=green
  htmlSymbols=#ff8800
  htmlComments=#abc
  ```

* the color scheme of the preview, using CSS.  
  Add `styleSheet=/home/YOUR_USERNAME/.config/ReText project/YOUR_FILE.css`  
  and `useWebKit=true` to the configuration file

  <ins>Example (preview.css)</ins>:

  ```
  body {
    color: black;
    background-color: white;
  }
  ```

Of course, don't forget to put the files in that directory, then restart ReText to see the changes.

## Prebuild Color Schemes

| Theme                              | CSS | QSS | Conf | Preview | Source
|---                                 |---  |---  |---   |---      |---
| [Default](Default)                 | ⨯   | ⨯   | ⨯    | ![](Default/preview.png?s=150)     | [retext-project](https://github.com/retext-project/retext/blob/master/ReText/highlighter.py)
| [Github](Github)                   | ✓   | ⨯   | ✓    | ![](Github/preview.png?s=150)      | [EndangeredMassa](https://gist.github.com/EndangeredMassa/8849279/)
| [QDarkStyle](QDarkStyle)           | ✓   | ✓   | ✓    | ![](QDarkStyle/preview.png?s=150)  | [snailhome](http://snailhome.github.io/note/do_someting_after_install_retext.html)
| [Monokai](Monokai)                 | ⨯   | ✓   | ✓    | ![](Monokai/preview.png?s=150)     | [geekthis](https://geekthis.net/post/retext-change-color-scheme/)
| [Monokai Minimal](Monokai-Minimal) | ⨯   | ✓   | ✓    | ![](Monokai-Minimal/preview.png?s=150)     | [geekthis](https://geekthis.net/post/retext-change-color-scheme/)
| [Solarized](Solarized)             | ⨯   | ✓   | ✓    | ![](Solarized/preview.png?s=150)     | [geekthis](https://geekthis.net/post/retext-change-color-scheme/)
| [Solarized Light](Solarized-Light) | ⨯   | ✓   | ✓    | ![](Solarized-Light/preview.png?s=150)     | [geekthis](https://geekthis.net/post/retext-change-color-scheme/)
| [Breeze Dark](Breeze-Dark)         | ✓   | ✓   | ✓    | ![](Breeze-Dark/preview.png?s=150) | [cognifloyd](https://github.com/retext-project/retext/issues/255#issuecomment-281764875)
| [Markdown Taupe](Markdown-Taupe)   | ✓   | ⨯   | ⨯    | ![](Markdown-Taupe/preview.png?s=150) | [jasonm23](https://github.com/jasonm23/markdown-css-themes/blob/gh-pages/screen.css)
| [Houdini](Houdini)                 | ✓   | ✓   | ✓    | ![](Houdini/preview.png?s=150) | [shotgunsoftware](https://github.com/shotgunsoftware/tk-houdini/blob/master/style.qss)
| [Markdown](Markdown)               | ✓   | ⨯   | ⨯    | ![](Markdown/preview.png?s=150) | [elclanrs](https://gist.github.com/elclanrs/f49c0a8cf3838c1ffeb3)

