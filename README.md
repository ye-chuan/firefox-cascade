<div align="center">

# Cascade

**A minimalistic and keyboard centered userChrome**

![Cascade Preview](assets/preview.webp)

Cascade aims to remove a lot of the subjective clutter default Firefox comes with. The theme is also highly inspired by the stylistic choices of [SimpleFox](https://github.com/migueravila/SimpleFox) 🦊 by [Miguel Ávila](https://github.com/migueravila).

<br>

<div style="display: flex; justify-content: center; gap: 1rem;">
  <a href="https://cascadefox.github.io/installation.html">
    <img
      alt="Install"
      src="https://img.shields.io/badge/firefox-install-c6a0f6?style=for-the-badge&logo=firefox&logoColor=white&labelColor=363a4f"
  /></a>
  <a href="https://github.com/cascadefox/cascade/stargazers">
    <img
      alt="Stargazers"
      src="https://img.shields.io/github/stars/cascadefox/cascade?style=for-the-badge&logo=starship&color=7dc4e4&logoColor=white&labelColor=363a4f"
  /></a>
  <a href="https://github.com/cascadefox/cascade">
    <img
      alt="Repo Size"
      src="https://img.shields.io/discord/837559961194070026?label=FFCSS+Discord&style=for-the-badge&logo=discord&color=a6da95&logoColor=white&labelColor=363a4f"
  /></a>
  <a href="https://github.com/cascadefox/cascade/issues">
    <img
      alt="Issues"
      src="https://img.shields.io/github/issues/cascadefox/cascade?style=for-the-badge&logo=gitbook&color=f5a97f&logoColor=white&labelColor=363a4f"
  /></a>
</div>

</div>

### My Fork
The main change is the addition of `includes/onetab-oneline.css` which enforces the 1 line bar even when the window is shrunk if we have only 1 tab in the window.

This repo is only for personal use, with changes that focuses on integration with specifically the **Catppuccin Mocha** theme.
- Added `--uc-selected-tab` color in `cascade-mocha.css` to fix the low contrast on the current tab
- Removed (commented out) style for the URL bar dropdown hovered / selected entry in `cascade-nav-bar.css`
    - Particularly the style for `.urlbarView-row:hover > .urlbarView-row-inner` and `.urlbarView-row[selected] > .urlbarView-row-inner`
    - The `--toolbar-field-focus-background-color` is used by Firefox to colour the entire dropdown box, hence the selected entry has no constrast

| Original                             | This Fork                           |
|--------------------------------------|-------------------------------------|
| ![Small Width Original](assets/small-width-original.png) | ![Small Width This Fork](assets/small-width-my-fork.png) |

---

### Documentation

**[Installation](https://cascadefox.github.io/installation.html) • [Customisation](https://cascadefox.github.io/customisation.html) • [Integrations](https://cascadefox.github.io/integrations.html) • [Keyboard Shortcuts](https://cascadefox.github.io/shortcuts.html)**

<br>
