<img src="./icon.png" width=128>

### About

Simple workaround for a bug in Contacts.app that pads copied phone numbers with zero-width characters, like this:

<img src="./zwsp.png" width=410>

### How to use

1. Download the latest release from [here](https://github.com/luckman212/alfred-copy-workaround/releases/download/1.0.1/CopyWorkaround.alfredworkflow)
2. Double-click on it to import it to Alfred
3. Next time you need to copy a phone number from Contacts.app:
   - click in the phone# field
   - press <kbd>⌘cmd</kbd><kbd>A</kbd> (Select All)
   - then press this workflow's trigger hotkey (<kbd>⌘cmd</kbd><kbd>⇧shift</kbd><kbd>C</kbd> by default)
4. The number will be copied without the extra garbage padding.

### References

- [Zero-width characters embedded in phone number whenever they are copied from the macOS address book](https://apple.stackexchange.com/questions/337101/zero-width-characters-embedded-in-phone-number-whenever-they-are-copied-from-the)
- specifically: [my answer](https://apple.stackexchange.com/a/350404/100302)
