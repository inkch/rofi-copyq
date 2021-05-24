# rofi-copyq

This is a fork from [cjbassi/rofi-copyq](https://github.com/cjbassi/rofi-copyq).

---

Use [Rofi](https://github.com/DaveDavenport/rofi) to search [CopyQ](https://github.com/hluk/CopyQ)'s clipboard history and set the clipboard to the selected snippet.

Requires:

- Rofi
- CopyQ

## Installation

```bash
pip install --user git+https://github.com/inkch/rofi-copyq
```

Note that `~/.local/bin` needs to be added to your `$PATH` for user installs.


## Usage

Simply run `rofi-copyq`, probably through Rofi itself, and then you can search and select a CopyQ snippet to be put on the current clipboard.
