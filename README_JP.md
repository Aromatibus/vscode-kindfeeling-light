<!-- markdownlint-disable MD033 -->
<!-- markdownlint-disable MD041 -->

![vscode-kindfeeling-light](https://github.com/Aromatibus/vscode-kindfeeling-light/raw/master/./screenshots/screenshot.png)

<p align="center">
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/version/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&label=marketplace&labelColor=30B1D2&color=38DBFA"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/installs-short/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF7F00&color=FF9731"/></a>
<a href="https://marketplace.visualstudio.com/items?itemName=Aromatibus.kindfeeling"><img src="https://vsmarketplacebadge.apphb.com/rating-star/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF8AD8&color=FEC0FC"/></a>
</p>

<p>
<a href="./README.md">📖English Description</a> /
<a href="./README_CN.md">📖中文的解释</a>
<a href="https://www.deepl.com/home"> （DeepLで翻訳いたしました。） </a>
</p>

# ⧉ 目次（Contents）
<!-- TOC -->

- [⧉ 目次（Contents）](#%E2%A7%89-%E7%9B%AE%E6%AC%A1contents)
- [⧉ インストール方法](#%E2%A7%89-%E3%82%A4%E3%83%B3%E3%82%B9%E3%83%88%E3%83%BC%E3%83%AB%E6%96%B9%E6%B3%95)
- [⧉ 自分の好みにカスタマイズしましょう](#%E2%A7%89-%E8%87%AA%E5%88%86%E3%81%AE%E5%A5%BD%E3%81%BF%E3%81%AB%E3%82%AB%E3%82%B9%E3%82%BF%E3%83%9E%E3%82%A4%E3%82%BA%E3%81%97%E3%81%BE%E3%81%97%E3%82%87%E3%81%86)
  - [使用フォント](#%E4%BD%BF%E7%94%A8%E3%83%95%E3%82%A9%E3%83%B3%E3%83%88)
  - [拡張機能を使ってさらに見た目を変更しましょう](#%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E3%81%95%E3%82%89%E3%81%AB%E8%A6%8B%E3%81%9F%E7%9B%AE%E3%82%92%E5%A4%89%E6%9B%B4%E3%81%97%E3%81%BE%E3%81%97%E3%82%87%E3%81%86)
    - [オススメの設定](#%E3%82%AA%E3%82%B9%E3%82%B9%E3%83%A1%E3%81%AE%E8%A8%AD%E5%AE%9A)
    - [こんな設定もあります](#%E3%81%93%E3%82%93%E3%81%AA%E8%A8%AD%E5%AE%9A%E3%82%82%E3%81%82%E3%82%8A%E3%81%BE%E3%81%99)
  - [スクリーンショットの背景について (*No support*)](#%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88%E3%81%AE%E8%83%8C%E6%99%AF%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6-no-support)
    - [拡張機能 "Background-cover" を使う場合](#%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD-background-cover-%E3%82%92%E4%BD%BF%E3%81%86%E5%A0%B4%E5%90%88)
    - [拡張機能を使わずに自分で書き換える場合](#%E6%8B%A1%E5%BC%B5%E6%A9%9F%E8%83%BD%E3%82%92%E4%BD%BF%E3%82%8F%E3%81%9A%E3%81%AB%E8%87%AA%E5%88%86%E3%81%A7%E6%9B%B8%E3%81%8D%E6%8F%9B%E3%81%88%E3%82%8B%E5%A0%B4%E5%90%88)
      - [設定ファイルの場所](#%E8%A8%AD%E5%AE%9A%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%81%AE%E5%A0%B4%E6%89%80)
      - [設定ファイルを書き換えます](#%E8%A8%AD%E5%AE%9A%E3%83%95%E3%82%A1%E3%82%A4%E3%83%AB%E3%82%92%E6%9B%B8%E3%81%8D%E6%8F%9B%E3%81%88%E3%81%BE%E3%81%99)
- [⧉ テーマを作成するにあたって](#%E2%A7%89-%E3%83%86%E3%83%BC%E3%83%9E%E3%82%92%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B%E3%81%AB%E3%81%82%E3%81%9F%E3%81%A3%E3%81%A6)
  - [🕮 闇って優しい感じなの？(Is the darkness kind feeling?)](#%F0%9F%95%AE-%E9%97%87%E3%81%A3%E3%81%A6%E5%84%AA%E3%81%97%E3%81%84%E6%84%9F%E3%81%98%E3%81%AA%E3%81%AEis-the-darkness-kind-feeling)
- [⧉ License](#%E2%A7%89-license)

<!-- /TOC -->

# ⧉ インストール方法

1. サイドバーから拡張機能アイコンを押してメニューを開きます。</br>
次に検索窓から"`Kindfeeling`"と検索します。</br>
<img src="https://code.visualstudio.com/assets/docs/editor/extension-gallery/extensions-view-icon.png" width="32"/> 拡張機能のアイコン
1. **Install**ボタンを押します。
1. サイドバーから管理アイコンを押してメニューを開きます。</br>
<img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/vscode_manage_icon.png" width="32"/> 管理のアイコン
1. 配色テーマを選択して、"`Kindfeeling`"を選びます。
1. 楽しんでください! 😊

# ⧉ 自分の好みにカスタマイズしましょう

## 使用フォント

- <img src="https://blogs.adobe.com/favicon.ico" width=14 height=14/> フォントの解説 [源ノ角ゴシック Source Han Code JP](http://adobe.ly/1JIehdg)
- <img src="https://github.com/favicon.ico" width=14 height=14/> GitHub [adobe-fonts/source-han-code-jp](https://github.com/adobe-fonts/source-han-code-jp)
- 🗛 ダウンロード [Fonts version 2.011R(OTF, OTC)](https://github.com/adobe-fonts/source-han-code-jp/archive/2.011R.zip)

## 拡張機能を使ってさらに見た目を変更しましょう

<table border="0" width="400">
<tbody>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/vscode"><img alt="Marketplace" src="https://marketplace.visualstudio.com/favicon.ico" width="12"> Marketplace</a>
    </td>
    <td align="center">
      <a href="https://code.visualstudio.com/updates/"><img alt="VScode" src="https://code.visualstudio.com/favicon.ico" width="12"> VScode</a>
    </td>
  </tr>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2">Bracket Pair Colorizer 2</a>
    </td>
    <td align="center">
      <a href="vscode:extension/CoenraadS.bracket-pair-colorizer-2"><img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png"></a>
    </td>
  </tr>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow">indent-rainbow</a>
    </td>
    <td align="center">
      <a href="vscode:extension/oderwat.indent-rainbow"><img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png"></a>
    </td>
  </tr>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight">Highlight</a>
    </td>
    <td align="center">
      <a href="vscode:extension/fabiospampinato.vscode-highlight"><img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png"></a>
    </td>
  </tr>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover">Background-cover</a>
    </td>
    <td align="center">
      <a href="vscode:extension/manasxx.background-cover"><img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png"></a>
    </td>
  </tr>
  <tr valign="middle">
    <td align="left">
      <a href="https://marketplace.visualstudio.com/items?itemName=QzSG.kitty-time">Kitty Time =(＾● ⋏ ●＾)= ෆ 😺</a>
    </td>
    <td align="center">
      <a href="vscode:extension/QzSG.kitty-time"><img src="https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png"></a>
    </td>
  </tr>
</tbody>
</table>

### オススメの設定

- VS Codeの設定を変更します。

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

### こんな設定もあります

- 各プロジェクトのルートフォルダーに `.vscode` フォルダーを作成しフォルダー内に`settings.json`ファイルを作成、以下のコードを追加するとプロジェクト毎に見た目を変更できます。

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

- ターミナルをBashにして、開いているソースと同じフォルダーで開く方法。</br>
`bash.exe`の場所はご利用の環境に合わせてください。

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

## スクリーンショットの背景について (*No support*)

- スクリーンショットに使用されている画像は、[images](https://github.com/Aromatibus/vscode-kindfeeling-light/blob/master/./images/) フォルダーに保存されています。

### 拡張機能 "[Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)" を使う場合

1. 画像の不透明度（opacity）は最初`0.5`くらいがオススメです。
1. "**[Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)**" の設定を直接変更します。
1. "`FileDom.js`" を変更して表示する画像の基準となる位置を左下にします。
1. ファイルの場所 : `~\.vscode/extensions\manasxx.background-cover-2.2.3\out\FileDom.js`.
1. 拡張機能のフォルダーは[こちら](https://vscode-docs.readthedocs.io/en/stable/extensions/install-extension/#your-extensions-folder)を参照してください。

1. 「*（アスタリスク）」の行を追加します。

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

### 拡張機能を使わずに自分で書き換える場合

#### 設定ファイルの場所

使用するOSごとに設定ファイルの場所を確認してください。

- <img src="https://www.microsoft.com/favicon.ico" width=14 height=14/> **Windows**</br>
  `\Visual Studio Code\Resource\app\out\vs\workbench\workbench.desktop.main.css`
- <img src="https://www.apple.com/favicon.ico" width=20 height=20/> **macOS**</br>
  `\Visual Studio Code.app\Contents\Resource\app\out\vs\workbench\workbench.desktop.main.css`
- <img src="https://www.cs.helsinki.fi/u/torvalds/linux_logo.gif" width=16 height=16/> **Linux**</br>
  `\Visual Studio Code\resources\app\out\vs\workbench\workbench.desktop.main.css`

#### 設定ファイルを書き換えます

1. 最初にファイル"`workbench.desktop.main.css`" のバックアップをしましょう。
1. ファイルの末尾に以下の設定を追加しましょう。
1. 画像の不透明度（opacity）は最初`0.5`くらいがオススメです。
1. `background-image`で指定する画像の場所は、自分の環境に合わせて変更します。
    - 以下の例では、Windowsの「`Visual Stdio Code`」フォルダー内に「`images`」フォルダーを作成し、画像を保存しています。
    - 以下の例ではポータブル環境向けにフォルダーを指定しています。

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

# ⧉ テーマを作成するにあたって

## [🕮 闇って優しい感じなの？(Is the darkness kind feeling?)](Is%20the%20darkness%20kind%20feeling.md)

結論からご紹介します</br>
画面の明るさを部屋と同じくらいか暗めにして、暖色系のライトテーマを使うのがオススメです。

# ⧉ License

<details>
  <summary>
    <a href="../aromatibus.kindfeeling/LICENSE.txt">𝐌𝐈𝐓 𝐋𝐢𝐜𝐞𝐧𝐬𝐞</a>
    &copy;
    <a href="[../aromatibus.kindfeeling/LICENSE.txt](https://github.com/Aromatibus)">𝓐𝓻𝓸𝓶𝓪𝓽𝓲𝓫𝓾𝓼</a>
  </summary>
  </br>
  </br>
  <img alt="GitHub last-commit"   src="https://img.shields.io/github/last-commit/Aromatibus/vscode-kindfeeling-light?style=for-the-badge&logo=GitHUB&labelColor=000000&color=808080">
  <img alt="GitHub repo-size" src="https://img.shields.io/github/repo-size/Aromatibus/vscode-kindfeeling-light?style=for-the-badge&logo=GitHUB&labelColor=000000&color=808080">
  </br>
  <img alt="version" src="https://vsmarketplacebadge.apphb.com/version/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&label=marketplace&labelColor=30B1D2&color=38DBFA"/>
  <img alt="installs-short" src="https://vsmarketplacebadge.apphb.com/installs-short/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF7F00&color=FF9731"/>
  <img alt="rating-star" src="https://vsmarketplacebadge.apphb.com/rating-star/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=FF8AD8&color=FEC0FC"/>
  </br>
  <img alt="downloads-short" src="https://vsmarketplacebadge.apphb.com/downloads-short/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&labelColor=007000&color=00C000"/>
  <img alt="trending-daily" src="https://vsmarketplacebadge.apphb.com/trending-daily/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&label=Daily&labelColor=0030C0&color=0050FF"/>
  <img alt="trending-weekly" src="https://vsmarketplacebadge.apphb.com/trending-weekly/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&label=Weekly&labelColor=900050&color=D00080"/>
  <img alt="trending-monthly" src="https://vsmarketplacebadge.apphb.com/trending-monthly/Aromatibus.kindfeeling.svg?style=for-the-badge&logo=visual-studio-code&label=Monthly&labelColor=E00000&color=F03030"/>
</details>

<!---

&#x1f60a;
&#x1f63b;

&#x1f56e;</br>
&#x29C9; &#x2751;</br>
&#9712; &#9713; &#9714; &#9715;</br>
&#x273B; &#x273C; &#x273D;</br>
&#11214;&#11047;&#11048;</br>

&#x2318;&#x21E7;
&#128475;

&#x01D40C;&#x01D408;&#x01D413; &#x01D40B;&#x01D422;&#x01D41C;&#x01D41E;&#x01D427;&#x01D42C;&#x01D41E; &#x01D4D0;&#x01D4FB;&#x01D4F8;&#x01D4F6;&#x01D4EA;&#x01D4FD;&#x01D4F2;&#x01D4EB;&#x01D4FE;&#x01D4FC;

Emoji-Log: A new way to write Git commit messages.
https://opensource.com/article/19/2/emoji-log-git-commit-messages

絵文字:メッセージサンプル
📦 新規(New):ファイルを追加
👌 改善(IMPROVE): .gitignore
🐛 修正(FIX): Readme.md
📖 ドキュメント(DOC): License.txt
🚀 リリース(RELEASE): バージョン2.0.0
✅ テスト(TEST): 模擬テスト
❌ 削除・失敗
🤖 TEST
‼️ BREAKING

[𝐌𝐈𝐓 𝐋𝐢𝐜𝐞𝐧𝐬𝐞](../aromatibus.kindfeeling/LICENSE.txt) &copy; [𝓐𝓻𝓸𝓶𝓪𝓽𝓲𝓫𝓾𝓼](https://github.com/Aromatibus)

[IMG_VSC]: https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/VSCode_logo(12x12).png

[BTN_Install]: https://raw.githubusercontent.com/Aromatibus/vscode-kindfeeling-light/master/images/BTN_Install(60x16).png

| ◳ Marketplace                                                                                                      |                               ![IMG_VSC][] VScode                                |
| :----------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------: |
| [Bracket Pair Colorizer 2](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2) | [![[Install]][BTN_Install]](vscode:extension/CoenraadS.bracket-pair-colorizer-2) |
| [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)                       |       [![[Install]][BTN_Install]](vscode:extension/oderwat.indent-rainbow)       |
| [Highlight](https://marketplace.visualstudio.com/items?itemName=fabiospampinato.vscode-highlight)                  |  [![[Install]][BTN_Install]](vscode:extension/fabiospampinato.vscode-highlight)  |
| [Background-cover](https://marketplace.visualstudio.com/items?itemName=manasxx.background-cover)                   |      [![[Install]][BTN_Install]](vscode:extension/manasxx.background-cover)      |
| [Kitty Time =(＾● ⋏ ●＾)= ෆ](https://marketplace.visualstudio.com/items?itemName=QzSG.kitty-time) 😺               |          [![[Install]][BTN_Install]](vscode:extension/QzSG.kitty-time)           |

--->
