<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->
<!---
&#x1f56e;
&#9712; &#9713; &#9714; &#9715;
&#x273B; &#x273C; &#x273D;
&#x29C9; &#x2751;
&#11214;&#11047;&#11048;
-->

![vscode-kindfeeling-light](https://github.com/Aromatibus/vscode-kindfeeling-light/raw/master/./screenshots/screenshot.png)

<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/version/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=30B1D2&color=38DBFA"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/installs-short/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF7F00&color=FF9731"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/rating-star/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF8AD8&color=FEC0FC"/></a>
</p>

# &#x29C9; Contents
<!-- TOC -->

- [&#x29C9; Contents](#%e2%a7%89-contents)
- [&#x29C9; Installation](#%e2%a7%89-installation)
- [&#x29C9; Personalization](#%e2%a7%89-personalization)
  - [Extensions needed to get the same look](#extensions-needed-to-get-the-same-look)
    - [Recommended settings](#recommended-settings)
    - [Tips Recommended settings](#tips-recommended-settings)
  - [&#x29C9; About the background of the screenshot  (*No support*)](#%e2%a7%89-about-the-background-of-the-screenshot-no-support)
    - [The extension "Background-cover" is used](#the-extension-%22background-cover%22-is-used)
    - [Rewrite directly by yourself](#rewrite-directly-by-yourself)
      - [Settings File Locations](#settings-file-locations)
      - [About rewriting contents](#about-rewriting-contents)
- [&#x29C9; Creating the theme](#%e2%a7%89-creating-the-theme)
  - [&#x1f56e; 闇って優しい感じなの？(Is the darkness kind feeling?)](#%f0%9f%95%ae-%e9%97%87%e3%81%a3%e3%81%a6%e5%84%aa%e3%81%97%e3%81%84%e6%84%9f%e3%81%98%e3%81%aa%e3%81%aeis-the-darkness-kind-feeling)
- [&#x29C9; License](#%e2%a7%89-license)

<!-- /TOC -->

# &#x29C9; Installation

1. Open the Extensions sidebar in VS Code.</br>
Next, search for the "`Kindfeeling`" theme.</br>
<img src="https://code.visualstudio.com/assets/docs/editor/extension-gallery/extensions-view-icon.png" width="32"/> Mark for expansions
1. Click **Install**.
1. Open the Command Palette with [***Ctrl+Shift+P***] or [**&#x2318;+&#x21E7;P**].
1. Select **Preferences: Color Theme** and choose a "`Kindfeeling`".
1. Enjoy ! &#x1f60a;

# &#x29C9; Personalization

## Extensions needed to get the same look

[IMG_VSC]: https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/VSCode_logo(12x12).png

[BTN_Install]: https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png

| &#9715; Marketplace                                                                                                |                               ![IMG_VSC][] VScode                                |
| :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------: |
| [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) | [![[Install]][BTN_Install]](vscode:extension/CoenraadS.bracket-pair-colorizer-2) |
| [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)                       |       [![[Install]][BTN_Install]](vscode:extension/oderwat.indent-rainbow)       |
| [Highlight](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight)                  |  [![[Install]][BTN_Install]](vscode:extension/fabiospampinato.vscode-highlight)  |
| [Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)                   |      [![[Install]][BTN_Install]](vscode:extension/manasxx.background-cover)      |
| [WordCounter](https://marketplace.visualstudio.com/items?itemName=kirozen.wordcounter)                             |        [![[Install]][BTN_Install]](vscode:extension/kirozen.wordcounter)         |
| [Kitty Time =(＾● ⋏ ●＾)= ෆ](https://marketplace.visualstudio.com/items?itemName=QzSG.kitty-time) &#x1f63b;        |          [![[Install]][BTN_Install]](vscode:extension/QzSG.kitty-time)           |

### Recommended settings

- Add or change VS Code settings.

    ```jsonc:settings.json
    {
      "editor.cursorStyle": "line",
      "editor.cursorWidth": 3,
      "editor.renderWhitespace": "boundary",
      "editor.minimap.side": "left",
      "editor.minimap.maxColumn": 40,
      "editor.minimap.renderCharacters": false,
      "editor.minimap.showSlider": "always",
      // extension "bracket-pair-colorizer-2"
      "bracket-pair-colorizer-2.colors": [
        "Green",
        "Red",
        "Blue",
        "Orange"
      ],
      // Highlight
      "highlight.regexFlags": "gi",
      "highlight.decorations": {
        "rangeBehavior": 3
      },
      "highlight.regexes": {
        "( {1,})[\\r?\\n]": [ // Space at the end of the line
          {
            "backgroundColor": "#FFC0F0",
            "borderColor": "#FF0086",
            "borderWidth": "1px",
            "borderStyle": "solid",
          }
        ],
        "(?<=\\S)( {2,})(?=\\S)": [ // Two or more spaces between characters
          {
            "borderColor": "#FF0086",
            "borderWidth": "1px",
            "borderStyle": "none none dashed none",
          }
        ],
        "(　)": [ // full-width space
          {
            "backgroundColor": "#FFC0F0",
            "borderColor": "#FF0086",
            "borderWidth": "1px",
            "borderStyle": "solid",
          }
        ],
        "([！"＃＄％＆'（）＝～｜'｛＋＊｝［］＜＞？＿－＾￥＠「；：」・])": [ // full-width sign
          {
            "borderColor": "#FF0086",
            "borderWidth": "1px",
            "borderStyle": "solid",
          }
        ],
      },
      "highlight.maxMatches": 250,
    }
    ```

### Tips Recommended settings

- It is convenient to create a `.vscode` folder in the root folder of each project and add the code in the `settings.json` file.

    ```json:settings.json
    {
      "workbench.colorCustomizations": {
        "titleBar.activeBackground": "#F0F0F0",
        "titleBar.activeForeground": "#101010",
        "activityBar.background": "#9B4A4A",
        "activityBar.foreground": "#FFFFFF",
      },
    }
    ```

- How to specify a terminal as Bash and open it in the same folder as the source.</br>
Please adjust the location of the bash.exe to your environment.

  ```json:settings.json
    {
      "terminal.integrated.shell.windows": "${env:windir}\\system32\\cmd.exe",
      "terminal.integrated.shellArgs.windows": [
        "/c",
        "cd /d ${fileDirname}",
        "& c:\\Git\\bin\\bash.exe"
      ],
    }
  ```

## &#x29C9; About the background of the screenshot  (*No support*)

- Images used for screenshots are stored in the [images folder](https://github.com/Aromatibus/vscode-kindfeeling-light/blob/master/./images/).

### The extension "[Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)" is used

1. We recommend adjusting the opacity from `0.5` at first.
1. Customize the "**[Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)**".
1. Rewrite "`FileDom.js`" and set the image display standard to the lower right.
1. File location : `~\.vscode/extensions\manasxx.background-cover-2.2.3\out\FileDom.js`.
1. [See here for the location of the file.](https://vscode-docs.readthedocs.io/en/stable/extensions/install-extension/#your-extensions-folder)

1. About rewriting contents. Add the lines marked with "\*(asterisk)".

    ```javascript:FileDom.js
    getCss() {
      // ???????
      let opacity = this.imageOpacity;
      opacity = opacity <= 0.1 ? 0.1 : opacity >= 1 ? 1 : opacity;
      opacity = 0.79 + (0.2 - ((opacity * 2) / 10));
      let imagePath = this.imagePath.replace(/\\/g, '/');
      return `
      /*ext-${this.extName}-start*/
      /*ext.${this.extName}.ver.${version_1.default}*/
      body{
        background-size:cover;
        background-repeat: no-repeat;
        opacity:${opacity};
        background-image:url('${imagePath}');
    *   background-position: right bottom;
    *   resize: both;
      }
      /*ext-${this.extName}-end*/
      `;
    }
    ```

### Rewrite directly by yourself

#### Settings File Locations

Depending on your platform, the settings file is located here:

- <img src="https://www.microsoft.com/favicon.ico" width=14 height=14/> **Windows**</br>
  `\Visual Studio Code\Resource\app\out\vs\workbench\workbench.desktop.main.css`
- <img src="https://www.apple.com/favicon.ico" width=20 height=20/> **macOS**</br>
  `\Visual Studio Code.app\Contents\Resource\app\out\vs\workbench\workbench.desktop.main.css`
- <img src="https://www.cs.helsinki.fi/u/torvalds/linux_logo.gif" width=16 height=16/> **Linux**</br>
  `\Visual Studio Code\resources\app\out\vs\workbench\workbench.desktop.main.css`

#### About rewriting contents

1. **Please backup** "`workbench.desktop.main.css`" first.
1. Add code to the end of the file.
1. We recommend adjusting the opacity from `0.5` at first.
1. Change the image and location specified in "`background-image`" according to your environment.

    - In the following example, the "`images`" folder is created in the "`Visual Stdio Code`" folder on Windows, and images are saved.

    - Useful for portable environments.

    ```css:workbench.desktop.main.css
    /*backgroundCover-start*/
    body{
      background-size: cover;
      background-repeat: no-repeat;
      opacity: 0.5;
      background-image: url('../../../../../background-images/angel_wings.png');
      background-position: right bottom;
      resize: both;
    }
    /*backgroundCover-end*/
    ```

# &#x29C9; Creating the theme

## [&#x1f56e; 闇って優しい感じなの？(Is the darkness kind feeling?)](Is%20the%20darkness%20kind%20feeling.md)

The text is in Japanese.

Let me just introduce the conclusion.</br>
It's better to use a warm color light theme with the same brightness of the screen as the room or as dark as possible.

# &#x29C9; License

[𝐌𝐈𝐓 𝐋𝐢𝐜𝐞𝐧𝐬𝐞](../aromatibus.kindfeeling/LICENSE.txt) &copy; [𝓐𝓻𝓸𝓶𝓪𝓽𝓲𝓫𝓾𝓼](https://github.com/Aromatibus)
