<p align="center">
Jump/delete across whole (non-whitespace) words with Ctrl+Left/Right/Delete/Backspace.
</p>

<p align="center">  
If you like the idea click ⭐ on the repo and <a href="https://twitter.com/intent/tweet?text=Nice%20xontrib%20for%20the%20xonsh%20shell!&url=https://github.com/xonsh/xontrib-whole-word-jumping" target="_blank">tweet</a>.
</p>


## Installation

To install use pip:

```bash
xpip install xontrib-whole-word-jumping
# or: xpip install -U git+https://github.com/xonsh/xontrib-whole-word-jumping
```

## Usage

```bash
xontrib load whole_word_jumping
```

* `Control+left/right`: Jump to previous/next whole word
* `Control+backspace`: Delete to beginning of whole word
* `Control+delete`: Delete to end of whole word
* `Shift+delete`: Delete whole word

Alt+Left/Right/Delete/Backspace remain unmodified:

* `Alt+left/right`: Jump to previous/next token
* `Alt+backspace`: Delete to beginning of token
* `Alt+delete`: Delete to end of token

## Known issues

Some terminals cannot differentiate between Backspace and Control+Backspace.
In this case, users can set `$XONSH_WHOLE_WORD_CTRL_BKSP = False` to skip
configuration of the Control+Backspace key binding.

## Credits

This package was created with [xontrib template](https://github.com/xonsh/xontrib-template).
