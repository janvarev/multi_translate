# Multi translate plugin for oobabooga/text-generation-webui

This plugin provide MORE translate options then google_translate

Features:
- **Save params in file**
- **Engines:**
  - GoogleTranslate - simple translate by default
  - LibreTranslate - for offline translation (you need to setup your own server https://github.com/LibreTranslate/LibreTranslate, or use demoserver online)
  - LocalAlpaca - auto-translate locally if you have Alpaca model loaded in text-generation-webui
  - OneRingTranslator - universal one-endpoint server to multiple translation engines https://github.com/janvarev/OneRingTranslator (require custom_url setup)
- **Additional options**:
  - disable input translation
  - disable output translation
  - add origin phrase to output translation
  - debug translation in console

## How to run this plugin

1. Download it
2. Move downloaded files to folder `extensions/multi_translate`
3. Run oobabooga bat with params: `--extensions multi_translate` or enable it on Settings tab
