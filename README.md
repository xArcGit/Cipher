# Hack The Box Theme for VS Code

A custom Visual Studio Code theme **inspired by Hack The Box**, designed to provide a comfortable and focused coding experience for hackers and developers. Developed with 💚 by xArcGit.

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/hackthebox/master/static/hero.png">
</p>

## Theme Preview

This theme puts the focus squarely on your code. No distractions, no overly saturated colors that might look good in a preview but can strain your eyes after a long coding session. We have carefully adjusted the syntax and semantic highlighting across all supported languages to ensure your coding environment stays clean and easy to navigate.

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/hackthebox/master/static/theme-perspective-2.png">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/hackthebox/master/static/htb-theme1.png">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/hackthebox/master/static/htb-theme2.png">
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/hackthebox/master/static/htb-theme3.png">
</p>

---

## Getting Started

To install the Hack The Box theme, follow the steps below:

### Installation via Visual Studio Code Marketplace

1. Open the **Extensions** sidebar in VS Code (`View → Extensions`).
2. Search for `HackTheBox`.
3. Click **Install** to add the theme to your editor.
4. Click **Reload** to activate the theme.
5. Set the theme by navigating to **File > Preferences > Settings > Workbench > Color Theme** and select **HackTheBox**.

### Installation via Command Line

You can also install the theme via Git by running the following commands:

```bash
$ git clone https://github.com/xarcgit/hackthebox.git ~/.vscode/extensions/HackTheBox
$ cd ~/.vscode/extensions/HackTheBox
$ npm install && npm run build
```

---

## Recommended Visual Studio Code Settings

For the best experience using the Hack The Box theme, apply these settings in your **settings.json**:

1. Open **settings.json** by pressing **ctrl+shift+p** or going to **File > Preferences > Settings**.
2. Add or update the following settings:

```json
{
  "editor.fontFamily": "Maple Mono SC NF",
  "editor.fontSize": 12,
  "editor.fontWeight": "300",
  "editor.lineHeight": 20,
  "editor.letterSpacing": 0.5,
  "editor.fontLigatures": true,
  "editor.wordWrap": "on",
  "editor.formatOnPaste": true,
  "editor.cursorBlinking": "smooth"
}
```

- **Maple Mono SC NF Font**: You can download it [here](https://github.com/subframe7536/Maple-font).
- **Material Icon Theme**: Enhance your VS Code with the Material Icon Theme, available [here](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme).

---

## License

The MIT License (MIT)

Copyright (c) 2020 HackTheBox Theme

Permission is granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit others to do so, subject to the following conditions:

The above copyright notice and this permission notice must be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

## Feedback and Contributions

We’re always working to improve the theme. If you have feedback or suggestions, please feel free to open an issue or contribute via our [GitHub Repository](https://github.com/xarcgit/hackthebox).
