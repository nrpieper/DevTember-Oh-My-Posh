# 🍁 DevTember - A Cozy Oh My Posh Theme

A comfortable and functional Oh My Posh theme, inspired by the warm colors of autumn. Perfect for developers who appreciate a clean and organized terminal environment.

VS Code
![DevTember Theme Screenshot](./screenshots/vs-code.png)

PowerShell
![DevTember Theme Screenshot](./screenshots/powershell.png)

---

## ✨ Features

- **🍂 Autumn Color Palette:** Enjoy warm, pleasant colors that are easy on the eyes during long coding sessions.
- **📑 Three-Line Layout:** A clean, multi-line structure that separates important information from your input area for maximum clarity.
- **🛠️ Developer-Focused:** Out-of-the-box support for essential tools:
  - Detailed **Git** status with icons for every state.
  - Automatic version display for **Node.js**, **Angular**, and **.NET**.
- **⚡ Admin Warning:** An instant visual indicator (`⚡`) appears when you're running a shell with administrative privileges.
- **✅ Command Status:** Immediately see if your last command was successful (✔) or failed (✘).

---

## 🚀 Installation

You can either install the theme directly from GitHub (recommended for easy setup) or by downloading the file locally.

### Prerequisites

1. Make sure you have the latest version of **[Oh My Posh](https://ohmyposh.dev/docs/installation/windows)** installed.
2. You need a **[Nerd Font](https://www.nerdfonts.com/)** installed and set as the font in your terminal. (I recommend *FiraCode Nerd Font* or *Cascadia Code PL*).

### Quick Install (from GitHub)

This method loads the theme directly from the internet, no download required.

1. Open your PowerShell profile file.

    ```powershell
    notepad $PROFILE
    ```

2. Add the following line to your profile:

    ```powershell
    oh-my-posh init pwsh --config "https://raw.githubusercontent.com/GrischaTDev/DevTember-Oh-My-Posh/main/devtember.omp.json" | Invoke-Expression
    ```

3. Save the file and reload your profile.

    ```powershell
    . $PROFILE
    ```

### Local Installation

This method uses a local copy of the theme file.

1. Download the `devtember.omp.json` file from this repository.
2. Move the file into your Oh My Posh themes folder. You can find the path by running this command in PowerShell:

    ```powershell
    $env:POSH_THEMES_PATH
    ```

3. Open your PowerShell profile file.

    ```powershell
    notepad $PROFILE
    ```

4. Add the following line to your profile:

    ```powershell
    oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/devtember.omp.json" | Invoke-Expression
    ```

5. Save the file and reload your profile.

    ```powershell
    . $PROFILE
    ```
