# 🛠️ hermes-mod - Edit Hermes skins with ease

[![Download hermes-mod](https://img.shields.io/badge/Download-hermes--mod-blue?style=for-the-badge)](https://github.com/Joello2925/hermes-mod)

## 🚀 What this app does

Hermes Mod helps you manage Hermes CLI skins in a web UI. It gives you a simple way to view, edit, and apply skins without doing the manual work yourself.

Use it to:
- list built-in skins and custom skins
- open a skin in a visual editor
- edit real Hermes skin fields
- change banner logo text
- edit hero text art
- save skins to `~/.hermes/skins/`
- activate a skin by updating `~/.hermes/config.yaml`
- view generated YAML and a live preview
- use several hero image styles, including braille, ASCII ramp, blocks, and dots

## 📥 Download and install

Use this link to visit the project page and download or run the app:

[https://github.com/Joello2925/hermes-mod](https://github.com/Joello2925/hermes-mod)

### 1. 1-Click Install

If you use Pinokio, search for Hermes Mod on https://pinokio.co and install it with one click.

### 2. Run with npx

If you already have Node.js on your Windows PC, you can run:

```bash
npx -y hermes-mod
```

This starts the published app right away.

### 3. Manual Install

If you want to run it by hand:

1. Go into the `app` folder
2. Open Command Prompt or PowerShell
3. Run:

```bash
npm install
```

Then start the app with the command listed in the app folder.

## 🖥️ Windows setup

Hermes Mod is meant for a normal Windows desktop or laptop. A recent version of Windows 10 or Windows 11 works well.

You should have:
- a working internet connection for the first install
- enough free space for the app and its files
- Node.js installed if you want to use `npx` or manual setup
- access to your user folder, since the app writes to `~/.hermes/`

If you use the 1-click install option, the tool handles most of the setup for you.

## 🧭 First run

After you install or launch Hermes Mod:

1. Open the app in your browser or local web view
2. Let it scan your Hermes skins
3. Pick a built-in skin or a custom skin
4. Open it in the editor
5. Change the fields you want
6. Save the skin
7. Activate it if you want it to become the current skin

The app keeps the process simple, so you can make changes without editing YAML by hand.

## 🎨 What you can edit

Hermes Mod works with the Hermes skin schema and lets you edit:

- colors
- spinner faces
- spinner verbs
- spinner wings
- branding strings
- tool prefix
- tool emoji overrides
- `banner_logo`
- `banner_hero`

It also lets you work with the generated banner logo text and higher-detail hero text art, which helps if you want a skin that looks right in the terminal.

## 👀 Preview and save

The editor shows two useful views:

- generated YAML
- live preview

This helps you check your changes before you save them. You can see how the skin will look and how the file will be written.

When you save, Hermes Mod writes the skin to:

```bash
~/.hermes/skins/
```

If you activate a skin, it updates:

```bash
~/.hermes/config.yaml
```

## 🧩 Hero image styles

Hermes Mod supports several hero image render styles, so you can choose the look that fits your skin.

Available styles include:
- braille
- ASCII ramp
- blocks
- dots

These styles help when you want a simple text image that still feels clear in the terminal.

## 📁 Skin files

Hermes Mod works with both built-in skins and custom skins.

Built-in skins are useful when you want a fast starting point. Custom skins are useful when you want your own look and feel.

The app reads and edits the same skin data that Hermes CLI uses, so the changes you make stay useful outside the editor.

## 🪟 Basic Windows steps

If you are on Windows and want the quickest path:

1. Open the GitHub page
2. Use the Pinokio option if you want a simple setup
3. Or run the `npx` command in Command Prompt
4. Wait for the app to load
5. Open the editor in your browser
6. Edit your skin and save it

If Windows asks for permission during setup, allow it so the app can finish installing and writing files.

## 🔧 Common use cases

Use Hermes Mod when you want to:
- change the default look of Hermes CLI
- build a custom terminal theme
- fix a banner that does not look right
- test several skin styles
- edit skin values without opening raw files
- switch between skins with less effort

## 🗂️ Repository info

- Repository: hermes-mod
- Topic: pinokio
- Project page: https://github.com/Joello2925/hermes-mod

## 🧠 How it works

Hermes Mod gives you a browser-based editor for Hermes skins. You select a skin, change the values, then save or activate it. The app handles the file work in the background and keeps the process simple for end users.

It is useful if you want a cleaner way to manage:
- visual theme settings
- terminal banner text
- text art styles
- skin switching

## 🔍 Troubleshooting

If the app does not start:
1. Check that Node.js is installed
2. Try the `npx -y hermes-mod` command again
3. Make sure your internet connection works
4. Confirm that the `~/.hermes/` folder exists after first use
5. Reopen the GitHub page and try the 1-click install path

If your skin does not appear:
1. Check the skins folder under `~/.hermes/skins/`
2. Open the app again so it can rescan
3. Make sure the skin file is valid
4. Save the skin again from the editor

If changes do not show up in Hermes CLI:
1. Confirm that the skin was activated
2. Check `~/.hermes/config.yaml`
3. Restart Hermes CLI
4. Reopen the editor and verify the selected skin