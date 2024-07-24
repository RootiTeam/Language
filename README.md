# Pancake-Language

These files contain translation strings used in Pancake.

### Adding new strings
Only English should be modified directly. To add new strings, add them ONLY to eng.ini. Crowdin will then synchronize them with itself and the new strings will be put up for translation within Crowdin.

### For maintainers
If you have issues with translation files being deleted, add a language mapping in the Crowdin config. Some issues arose with Chinese due to Chinese Simplified and Chinese Traditional both mapping to `zho`, requiring a mapping to `zho-cn` for simplified.