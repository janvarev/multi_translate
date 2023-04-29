# Multi translate plugin for oobabooga/text-generation-webui

This plugin provide MORE translate options then google_translate

Features:
- Save params in file 
- LibreTranslate - for offline translation (you need to setup your own server https://github.com/LibreTranslate/LibreTranslate, or use demoserver online)
- LocalAlpaca - auto-translate locally if you have Alpaca model loaded in text-generation-webui
- Options to:
  - disable input translation
  - disable output translation
  - add origin phrase to output translation
  - debug translation in console

## How to run this plugin

1. Download it
2. Move downloaded files to folder `extensions/multi_translate`
3. Run oobabooga bat with params: `--extensions multi_translate` or enable it on Settings tab
