# 🔧 Firefox Compact Theme Installation Guide

This guide explains how to install the `userChrome.css` created by **Anuprash Subedi** to reduce the height of the tab bar and address bar in Firefox for a cleaner, more compact look.

---

## 🛠 Prerequisite: Enable Custom Stylesheets in Firefox

1. Open Firefox.

2. In the address bar, go to: `about:config`
    ![Search 'About::config'](/firefox-compact-theme/images/config.png)

3. Search for: `toolkit.legacyUserProfileCustomizations.stylesheets`

4. Double-click it to set the value to `true`.
    ![Double click on 'false'](/firefox-compact-theme/images/pasting.png)

5. Restart Firefox.

---

## 💻 Installation Instructions by OS

### 🪟 Windows

1. Press `Win + R`, paste the following : %APPDATA%\Mozilla\Firefox\Profiles  , and press Enter:

2. Open the folder ending in `.default-release` (e.g., `abc123.default-release`).

3. Create a folder named `chrome` inside it (if it doesn’t exist).

4. Inside the `chrome` folder, create a file named: `serChrome.css`

5. Open it with **Notepad** (or any text editor) and paste the CSS from this repository.

6. Save and close the file.

7. Restart Firefox.

---

### 🍎 macOS

1. Open Finder.

2. Press `Cmd + Shift + G` and go to: ~/Library/Application Support/Firefox/Profiles

3. Open the profile folder ending in `.default-release`.

4. Create a folder named `chrome` if it doesn’t already exist.

5. Inside that, create a file named `userChrome.css`.

6. Open it using **TextEdit** or use the terminal:

```sh
nano ~/Library/Application\ Support/Firefox/Profiles/yourprofile.default-release/chrome/userChrome.css

    Paste the CSS code, save, and exit.

    Restart Firefox.

###🐧 Linux

    Open a terminal or file manager.

    Go to:

`~/.mozilla/firefox`

Find your profile folder (e.g., abc123.default-release).

Inside it, create a folder called `chrome`.

Create a file named `userChrome.css` in that folder.

Use any text editor, such as:

nano ~/.mozilla/firefox/yourprofile.default-release/chrome/userChrome.css

Or use a GUI editor like Gedit/Kate/VSCode.

Paste the CSS code into the file and save.

Restart Firefox.