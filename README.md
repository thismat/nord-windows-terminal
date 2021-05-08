<p align="center"><a href="https://github.com/thismat/nord-windows-terminal" target="_blank"><img src="https://github.com/thismat/nord-windows-terminal/blob/master/screenshot.png?raw=true"/></a></p>

<p align="center">An arctic, north-bluish clean and elegant <a href="https://github.com/microsoft/terminal">Windows Terminal</a> color theme.</p>


# Getting Started

This is an _unofficial_ port of [Nord](https://www.nordtheme.com/) to Windows Terminal. Visit [Nord Theme](https://www.nordtheme.com/) for more information about the theme. 


> An arctic, north-bluish color palette.
 Created for the clean and uncluttered design pattern to achieve a optimal focus and readability for code syntax highlighting and UI components.

## Install

<details>
<summary>Install with Powershell Script</summary>
    1. Clone the repository
    2. Open powershell and run install.ps1
    3. Restart windows terminal
    4. Set your colorschemes to Nord
</details>

<details>
<summary>Install by cloning the repository</summary>
    1. Clone the repository
    2. Copying the contents of `nord.json` into your Windows Terminal `profile.json` `scheme` section. (There is a trailing comma for quick CTRL+A, CTRL+P).
</details>

Simply copy the JSON from `nord.json` or from this page, into the `schemes` section of Windows Terminal `profile.json`.

```json
{
    "name" : "Nord",
    "background" : "#2E3440",
    "foreground" : "#E5E9F0",
    "black" : "#3B4252",
    "blue" : "#81A1C1",
    "cyan" : "#88C0D0",
    "green" : "#8FBCBB",
    "purple" : "#B48EAD",
    "red" : "#BF616A",
    "white" : "#4C566A",
    "yellow" : "#EBCB8B",
    "brightBlack" : "#3B4252",
    "brightBlue" : "#5E81AC",
    "brightCyan" : "#88C0D0",
    "brightGreen" : "#A3BE8C",
    "brightPurple" : "#B48EAD",
    "brightRed" : "#BF616A",
    "brightWhite" : "#E5E9F0",
    "brightYellow" : "#EBCB8B"
},
```
_There is a trailing comma to make the copy/paste experience easier_

## Activation

In your Windows Terminal `profile.json` simply enter the themes name `Nord` as the `colorScheme` property to activate the theme for that profile.

```json
{
    "colorScheme" : "Nord",
    "fontFace" : "FiraCode Nerd Font Mono",
    "fontSize": 11,
    "guid": "...",
    "name": "PowerShell",
    "source": "Windows.Terminal.PowershellCore"
},
```
