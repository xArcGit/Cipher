# Cipher Theme for VS Code

A custom Visual Studio Code theme **inspired by Hack The Box**, designed to provide a comfortable and focused coding experience for hackers and developers. Developed with 💚 by xArcGit.

<p align="center">
  <img src="https://raw.githubusercontent.com/xarcgit/Cipher/master/static/hero.png">
</p>

## Getting Started

To install the Cipher theme, follow the steps below:

### Installation via Visual Studio Code Marketplace

1. Open the **Extensions** sidebar in VS Code (`View → Extensions`).
2. Search for `Cipher`.
3. Click **Install** to add the theme to your editor.
4. Click **Reload** to activate the theme.
5. Set the theme by navigating to **File > Preferences > Settings > Workbench > Color Theme** and select **Cipher**.

### Installation via Command Line

You can also install the theme via Git by running the following commands:

```bash
$ git clone https://github.com/xarcgit/Cipher.git ~/.vscode/extensions/Cipher
$ cd ~/.vscode/extensions/Cipher
$ npm install && npm run build
```

---

## Recommended Visual Studio Code Settings

For the best experience using the Cipher theme, apply these settings in your **settings.json**:

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

## [License](https://raw.githubusercontent.com/xarcgit/hackthebox/master/LICENSE)

## Feedback and Contributions

We’re always working to improve the theme. If you have feedback or suggestions, please feel free to open an issue or contribute via our [GitHub Repository](https://github.com/xarcgit/hackthebox).
