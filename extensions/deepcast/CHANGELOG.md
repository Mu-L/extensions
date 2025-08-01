# Deepcast Changelog

## [Default Formality Configuration] - 2025-06-07

- Added new "Default Formality" preference option to set a global formality level for all supported languages

## [Return to Root State] - 2025-05-27

- Added preference option to reset Raycast to root state after copying the translated text
- Improves workflow by allowing users to quickly return to the root state after translation
- Works in combination with "Close Raycast After Translation" preference for flexible behavior

## [Close Raycast After Translation] - 2025-05-26

- Added preference option to automatically close Raycast after getting translation result
- Improves workflow speed for quick translations by eliminating the need to manually close Raycast
- Works with all translation commands and actions (copy to clipboard, paste, view)

## [Arabic Support as Default Target Language] - 2025-04-15

- Arabic is now accepted as a default target language.

## [Formality] - 2024-12-02

- Better icon for switch languages action
- Added support for formality
- Added preference to show/hide transliteration
- Added preference to show/hide formality configuration

## [More Languages] - 2024-10-21

- Added Translate to Arabic

## [Error Handling] - 2024-05-31

- Added error message when the `Translate` command is disabled

## [Enhancement] - 2023-11-03

- Default to selected text for the `Translate` command
- Added action to copy the translation in the `Translate` command
- Added action to paste the translation to frontmost app in the `Translate` command
- Support fallback text for the `Translate` command
- Add support for optional transliteration (romanization) for all commands. Uses https://github.com/sindresorhus/transliterate

## [Arguments] - 2023-10-28

- Support arguments for `Translate Into ...` commands

## [Default Target Language and Fallback] - 2023-10-16

- Added preferences to set the default target language for `Translate Into ...` commands
- Support fallback text for `Translate Into ...` commands

## [More Input/Output Options] - 2023-10-05

- Added preferences to prefer clipboard or selected text over the other as input for `Translate Into ...` commands
- Added option to copy the translated text to the clipboard for `Translate Into ...` commands

## [New Additions] - 2023-07-04

- Added option to view translations in a Raycast window.
- Added Loading indicator toast while fetching translations.

## [More Languages] - 2023-04-14

- Added Translate to Turkish, Korean, Indonesian, and Norwegian
